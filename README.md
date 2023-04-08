# A Queue is a first in first out type of data structure. It has many applications in web development, Cbu and drive scheduling, routers etc. Algorithm to add a simple Queue using array is:
1.begin procedure peek
   return queue[front]
end procedure
2.begin procedure isfull

   if rear equals to MAXSIZE
      return true
   else
      return false
   endif
   
end procedure
3.begin procedure isempty

   if front is less than MIN  OR front is greater than rear
      return true
   else
      return false
   endif
   
end procedure
4.procedure enqueue(data)      
   
   if queue is full
      return overflow
   endif
   
   rear ← rear + 1
   queue[rear] ← data
   return true
   
end procedure
5.procedure dequeue
   
   if queue is empty
      return underflow
   end if

   data = queue[front]
   front ← front + 1
   return true

end procedure

