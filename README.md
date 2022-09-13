# list_of_textfield

A new Flutter project.

## Getting Started


##List of TextField



how to create list of textfiled

List<TextEditingController> _controllers = [];


ListView.builder(
itemCount: _counter,
itemBuilder: (context,index){
_controllers.add(new TextEditingController());
       return TextField(
              controller: _controllers[index],
       );
}),



how to get value

controllers[index].text