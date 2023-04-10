## How to add PlantUML to a markdown file


Code:

```plantumlcode
@startjson
{
   "fruit":"Apple",
   "size":"Large",
   "color": ["Red", "Green"]
}
@endjson

```

Output:

```plantuml
@startjson
{
   "fruit":"Apple",
   "size":"Large",
   "color": ["Red", "Green"]
}
@endjson

```

Code: 

```plantumlcode
@startuml
if (condition?) then
  #pink:error;
  kill
endif
#palegreen:action;
@enduml
```

```plantuml
@startuml
if (condition?) then
  #pink:error;
  kill
endif
#palegreen:action;
@enduml
```