gid
===
<br/>
I want to implement a gid service providing HA. Gid  service's full name is global  auto-incrementing  id generator service. I ever implemented a gid service not providing HA. Although it still work well util now, I want to implement one with full functions. Aha, it is just for fun and practicing code skill.<br/>


###preface
I find there is no any frameworks in company, which can be reused (maybe I just more like to do it by myself, aha). So I decide to implement all parts, e.g. client-side module, server-side module, rpc module... (wow, are you kidding me?)<br/>


###focus
Come up to the chalk, I plan to use third-party components below:

    thrift or google protobuf -- for rpc, serilization.
    zookeeper -- for HA implementation, cluster configuration management.
    postgresql -- for auto-incrementing id
    (maybe netty .. ?)
<br/>
Obviously, the increament part is easy, the hard part will be in others.<br/>
finally, sorry for my poor English, forgive me %>_<%<br/>
