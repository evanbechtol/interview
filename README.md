https://codesandbox.io/p/sandbox/elegant-moon-lsj726?file=%2Fsrc%2FApp.tsx

Wireframe:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/86966b8e-1772-4aac-b947-e7ff65c1a9dc" />


# Requirements
You have been given a task to design a proof-of-concept application, which will allow users to manage their inventories. 

The application should implement the following minimum requirements: 
- Should allow users to add inventory items to the list of items
- Should allow users to remove inventory items from the list of itemsShould allow users to modify the name of the item
- Should allow users to modify the available quantity of the item
- Should allow users to mark an item as tax-exempt using a checkbox Inventory items have the following structure: { name: string, quantity: number, taxExempt: boolean }

Additional requirements (but not day 1): 
- Should be able to toggle between showing or hiding items that are not in stock (there are no items available)
- Should be able to show or hide tax exempt items
- Should be able to sort the list of items by their names or available quantity
