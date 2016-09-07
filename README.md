# Autofac.Extras.DynamicProxy.Core
对官方Autofac.Extras.DynamicProxy的Core版移植

+ InterceptTransparentProxy相关方法中使用了System.Runtime.Remoting类库，由于微软官方还未提供，所以暂时为不可用状态，其他方法不受影响