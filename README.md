
# Review iOS Development 

1. Method Swizzling (runtime.h) - Can thiêp, thay thế 1 hàm bất kỳ, hooking 
  - http://nshipster.com/method-swizzling/
  - https://blog.newrelic.com/2014/04/16/right-way-to-swizzle/

2. HEAP and STACK  (Quản lý vùng nhớ HEAP và STACK trong iOS nhằm tối ưu RAM)


3. NSMutable (Sự khác nhau)


4. Mutable copy and copy diffirent


5. Theard 
  - Dispatch Queues
  - Serial queue
  - Concurrent queue
  - NSOperation
  (https://viblo.asia/hungbv/posts/DljMbo8ZGVZn)


6. Parten (MVC, MVP)
  (https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.rt362vlkz)


7. Reaction Programing


8. Block 
  Sử dung biến bên ngoài vào trong block (Vùng nhớ stack vào vùng nhớ Heap)
  
  
9. Protocal Delegate and Datasource


10. NSNotification 


11. KVC (Key-Value Coding)


12. KVO (Key-Value Observing)


13. Autolayout - Visual code - Frame 


14. Libary for iOS (Alrmofire, AFNetwoking,....)


15. List (NSArray, NSDictionay, NSSet)


16. Build Target in iOS, Script Build Phares


17. Elements Key Sanbox


18. Upload Appstore


19. Database (SQLite, Core Data, Realm,...)


20. MEMORY (Instrument tool)


21. Basic (Search, Sort,...)


22. Weak and Strong, Retain, Assign

23. Life circle

24. Deep copy anf Shallow copy 
https://developer.apple.com/library/content/documentation/General/Conceptual/DevPedia-CocoaCore/ObjectCopying.html

25. Atomic and Non-Atomic
	
Atomic: is the default behavior will ensure the present process is completed by the CPU, before another process accesses the variable is not fast, as it ensures the process is completed entirely

Non-Atomic: is NOT the default behavior faster (for synthesized code, that is, for variables created using @property and @synthesize) not thread-safe may result in unexpected behavior, when two different process access the same variable at the same time

http://stackoverflow.com/questions/588866/whats-the-difference-between-the-atomic-and-nonatomic-attributes

26. ....

