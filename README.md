# HomeWork5
List <Map<String , dynamic>> names =[{"name":"Aziz","Phone":032 ,"Location":"Riyadh"}];
void main(List<String> arguments) {

printALLName();
printFirstName();
}


printALLName(){
  for (var name in names) {
    print(name);
  }
}

printFirstName(){
  print(names["name"]);
}
