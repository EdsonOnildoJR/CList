# CList

These functions are declared in the **```CList.h```** header file:

* [ListInit](#listinit)
* [ListFree](#listfree)
* [ListAdd](#listadd)
* [ListGet](#listget)
* [ListRemove](#listremove)
* [ListSet](#listset)
* [ListSize](#listsize)

___

### ListInit

```c
List ListInit(void);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L12)

Returns a new list.

___

### ListFree
```c
List ListFree(List l);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L29)

Frees the memory used by the list.

___

### ListAdd

```c
void ListAdd(List *l, void *e);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L37)

Appends the specified element to the end of the list.

___

### ListGet

```c
void *ListGet(List l, int i);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L43)

Returns the element at the specified position in the list.

___

### ListRemove

```c
void ListRemove(List *l, int i);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L48)

Removes the element at the specified position in the list.

___

### ListSet

```c
void ListSet(List *l, int i, void *e);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L54)

Replaces the element at the specified position in the list with the specified element.

___

### ListSize

```c
int ListSize(List l);
```

[Source Code](https://github.com/EdsonOnildoJR/CPack/blob/d7360aeab7d9f135db6c2c9460d9a78c44bc179d/src/CPack/CList/CList.c#L59)

Returns the number of elements in the list.