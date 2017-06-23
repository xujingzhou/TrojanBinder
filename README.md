# TrojanBinder

  Trojan file binder. Compiled by VC6/VS2010 and Tested on Win2000/Win10.

  文件捆绑器可用来将二个不同的可执行文件合并成一个文件，运行合并后的文件等同于同时运行合并前的二个文件，并提供同步和异步运行二种方式，操作十分简便。

注意：
  如果文件编释后不能运行的原因可能是：1、请把它置为RELEASE版再编释。2、可能是编释器设置不同，使最终生成文件大小不同，请把您RELEASE版编释后的文件大小记下，在CBindFileDlg类中的初始对话框类OnInitDialog中的最后，把原来的文件大小184K，替换后您新编释后的文件大小既可。

徐景周(Johnny Xu)

未来工作室(Future Studio)
