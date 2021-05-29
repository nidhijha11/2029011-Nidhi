class Node:
    def __init__(self, data=None):
        self.data = data
        self.next = None
class singly_linked_list:
    def __init__(self):
        self.tail = None
        self.head = None
        self.count = 0

    def iterate_item(self):
        current_item = self.tail
        while current_item:
            val = current_item.data
            current_item = current_item.next
            yield val

    def append_item(self, data):
        node = Node(data)
        if self.head:
            self.head.next = node
            self.head = node
        else:
            self.tail = node
            self.head = node
        self.count += 1

items = singly_linked_list()
items.append_item('PHP')
items.append_item('Python')
items.append_item('C#')
items.append_item('C++')
items.append_item('Java')

for val in items.iterate_item():
    print(val)
![Exp12](https://user-images.githubusercontent.com/82803957/120068677-91992d00-c09f-11eb-9952-f56af319ef6a.png)
