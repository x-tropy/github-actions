不同 job 之间生成的文件不共享，用 actions/upload-artifact@v4 上传以备用

如果要保存文件至某个文件夹中，需手动先创建不存在的文件夹

actions/checkout@v4 都用 v4，node 版本升级了，以前的不要用

通过 with:name: 去找某个 artifact，这个更像是 id。而 path 是文件路径（包括文件名本身）
