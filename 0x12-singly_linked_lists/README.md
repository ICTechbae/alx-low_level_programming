- Singly linked lists

Tests ✔️
* Tests: This Directory is for tests purposes.

Header File 📁
* lists.h: Header file containing definitions and prototypes for all types and functions written for the project.
Type/File	Definition/Prototype
* struct list_s		•	char *str
* unsigned int len
* struct list_s *next
typedef list_t	struct list_s
0-print_list.c	size_t print_list(const list_t *h);
1-list_len.c	size_t list_len(const list_t *h);
2-add_node.c	list_t *add_node(list_t **head, const char *str);
3-add_node_end.c	list_t *add_node_end(list_t **head, const char *str);
4-free_list.c	void free_list(list_t *head)

Tasks 📃
* 0. Print list
* 1. List length
* 2. Add node
* 3. Add node at the end
* 4. Free list
* 5. The Hare and the Tortoise
* 6. Real programmers can write assembly code in any language
