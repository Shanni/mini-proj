class LRUCache(object):
    
    def __init__(self, capacity):
        """
        :type capacity: int
        """
        self.capacity=capacity
        self.l=[]
        self.d={}
        

    def get(self, key):
        """
        :rtype: int
        """
        return self.d[key]
        

    def set(self, key, value):
        """
        :type key: int
        :type value: int
        :rtype: nothing
        """
        if self.capacity==0:
            temp=self.l.pop(0)
            del d[temp]
            capacity+=1
        self.l.append(key)
        self.d[key]=value
        capacity-=1
lru=LRUCache(1)
