Operation guide: 
    1. add -javaagent:/path/to/ja-netfilter.jar to your vmoptions (manual or auto)
    2. plugin 'mymap' has been deprecated since version 2022.1
    3. don't care about the activation time, it is a fallback license and will not expire

Enjoy it~

JBR17:
    add these 2 lines to your vmoptions file: (for manual, without any whitespace chars)
    --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
    --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED