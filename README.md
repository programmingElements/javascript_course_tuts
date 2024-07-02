# javascript_course_tuts
A Javascript Course Tutorials

How Javascript Works
1. Call Stask 
2. Event Loop
3. Web Apis & Browser Environment
4. Task Queues [Task Queue] [Micro Task Queue] 
5. Async Task API
6. Fetch (Promise Based API)

Micro Task Queue
----------------
1. The MicroTask Queue is another queue in the runtime with a higher priority than the task queue. 
   
   The queue is specially dedicated to:
      1. Promise handler callbacks [then(callback), catch(callback), and finally(callback)]
      2. Execution of async function bodies following await 
      3. Mutation Observer callback
      4. QueueMicroTask callback

Official Link : https://www.youtube.com/watch?v=UXWBl77dq3A&t=778s