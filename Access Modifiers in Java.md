The access modifiers in Java used to modify or restrict the access of a class, constructor, variable, method or data member. There are four types of access modifiers.

| Modifier  | Same Package <br> Sub Class| Same Package <br>Non-Sub Class | Different Package<br>Sub Class  |  Different Package<br>Non-Sub Class  |
|-----------|--------------|---------------|--------------------|---------------------|
| public    |    Yes       |    Yes        |      Yes           |       Yes           |
| protected |    Yes       |    Yes        |      Yes           |       No            |
| default   |    Yes       |    Yes        |      No            |       No            |
| private   |    No        |    No         |      No            |       No            |

Note : All types of modifiers can be accessed in same class.
