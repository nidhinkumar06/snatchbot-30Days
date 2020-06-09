<div align="center">
  <h1>SnatchBot - Day 9</h1>
  <p>SnatchBot Logical Operations</p>
</div>

We can add logical operations for our bot to handle response.Some of the logical operators are 

* Equal to
* Greater than Equal to
* Less than
* Greater than


For example if you have multiple interactions and based on the response of each interaction if you want to display the response it can be done like below

```
[IF([responseTo interaction=1789382 fallback=TEXT]=2){[IF([responseTo interaction=1789385 fallback=TEXT]=3){[IF([responseTo interaction=1789441 fallback=TEXT]=1){[IF([responseTo interaction=1789507 fallback=TEXT]=1){Sub-acute mastitis with feed intake}]}]}]}]
```

It is not possible to add and or conditions in the statement and the response which needs to be displayed to the user should be given inside the { Give me the result }

If we give spaces between the condition it won't work.Instead of number if the user type a value how it will be validated should be checked out
