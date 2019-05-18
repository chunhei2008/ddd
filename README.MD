


- UI
    - 用户界面处理和用户的数据录入
- Application
    - 按模块分别定义不用的Service来讲述每一个操作下的"故事"
- Application.DomainEventSubscribers
    - 所有领域事件订阅者    
- Domain
    - 存放战术建模的结晶，Entity、Aggregate、ValueObject
- Domain.Events
    - 所有领域事件
- Domain.IRepositories            
    - 所有的仓储（资源库）接口
- Domain.Service
    - 领域服务，存放着那些不适合放在聚合/值对象上的无状态的操作方法，用于实现特定某个领域的任务
- Infrastructure
    - 存放着一些通用类库
- Intrastructure.Repositories
    - 所有的仓储（资源库）的实现
- Intrastructure.Translators
    - 翻译层，也就是与外部系统沟通的桥梁，主要的职责就是做好"防腐层"的重任                