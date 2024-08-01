# typesOfParameters

void main(){
  
  //Positioned parameters
  Map returnAnswer = userData("ammar",23,173.2,9);
  print(returnAnswer);
  
  //named parameters
  Map newreturnAnswer = newuserData(name: "Ammar",age: 23,height: 173.3,classLearning: 9);
  print(newreturnAnswer);
}

//positioned parameter
Map userData(String name, int age, double height, int classLearning){
  return {
    "name" : name,
    "age" : age,
    "height" : height,
    "class" : classLearning
  };
  
//Named parameters
  
}

//named Parameters
Map newuserData({required String name,required int age,required double height,required int classLearning}){
  return {
    "name" : name,
    "age" : age,
    "height" : height,
    "class" : classLearning
  };
}

OUTPUT: 
{name: ammar, age: 23, height: 173.2, class: 9}
{name: Ammar, age: 23, height: 173.3, class: 9}
