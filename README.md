# AndroidIDEBackup
下载 release 中的压缩包放进sdcard根目录



打开AndroidIDE的终端，使用以下cd命令进入androidide的根目录

<pre>cd /data/data/com.itsaky.androidide/files</pre>




使用tar命令解压缩 androidide_backup.gz，此操作会覆盖原始数据，请做好您的备份

<pre>tar -zxf /sdcard/androidide_backup.gz
 --recursive-unlink --preserve-permissions</pre>



等待解压完成，这可能需要一些时间，解压完成之后重启androidIED即可
