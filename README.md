# fileShaking
webpack插件：删除没有被依赖的业务文件

### blog 
https://segmentfault.com/a/1190000041496835

### options
{
  excludeRegex: [ // 排除的文件
      /readme\.md/i, // 不删除readme文件
      /utils/ // 不删除工具方法目录下的文件
  ],
  delete: true // 是否删除文件
}
