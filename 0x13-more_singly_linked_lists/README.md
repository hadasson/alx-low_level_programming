0. Print list
mandatory
Write a function that prints all the elements of a listint_t list.




1. List length
mandatory
Write a function that returns the number of elements in a linked listint_t list.
 
Prototype: size_t listint_len(const listint_t *h);

2. Add node
mandatory
Write a function that adds a new node at the beginning of a listint_t list.

Prototype: listint_t *add_nodeint(listint_t **head, const int n);


3. Add node at the end
mandatory
Write a function that adds a new node at the end of a listint_t list.

Prototype: listint_t *add_nodeint_end(listint_t **head, const int n);

4. Free list
mandatory
Write a function that frees a listint_t list.

Prototype: void free_listint(listint_t *head);

5. Free
mandatory
Write a function that frees a listint_t list.

Prototype: void free_listint2(listint_t **head);
The function sets the head to NULL
