include('index.php');
$contents = file_get_contents('README.md');
$Parsedown = new Parsedown();
echo $Parsedown->text($contents);
