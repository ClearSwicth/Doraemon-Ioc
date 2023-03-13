# DoraemonIoc
dependency injection(依赖注入)

use DoraemonIoc\Container

/**
 * 注册服务
 * @param1:给绑定服务起的别名
 * @param2:具体类的路径，也可以是回掉函数
 */
 Container::bind("test","test.php");
 
 /**
 * 使用
 */
 Container::make("test");
 
 /**
 * 当然你也可以直接绑定和是使用放在一起
 */
  Container::make("test",'test,php');
 
