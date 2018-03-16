# packer-example
Hashicorp packer getting started example

provisioners - takes your immutable generic servers and turns them into application spcefic services. (servers->services)
```
"provisioners":[
{
    "type": "shell",
    "scrypt": "makeAwesome.sh",
    "only":["myCoolThing"]
},
{
    
}
]

```
