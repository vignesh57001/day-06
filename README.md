# day-06
------------------------------------------------------------------

1) Blob/master/movie practice :

class Movie{
    constructor(title,studio,rating){
      this.title=title;
      this.studio=studio;
      this.rating=rating;
    }
  }
  var m1=new Movie("baahubali","arka media works",8.0);
  var m2=new Movie("money heist","vancouver media",8.2);
  var m3=new Movie("vikram","raj kamal films",8.5);
  var m4=new Movie("drishyam","panorama studios",8.2);
  console.log(m2,m4)

------------------------------------------------------------------------
2)Blop/master/class circle - practice :



-------------------------------------------------------------------------

3)A person class to hold all details :

class Person{
    constructor(name,dob,age,gender,occupation,address){
      this.name=name;
      this.dob=dob;
      this.age=age;
      this.gender=gender;
      this.occupation=occupation;
      this.address=address;
    }
    
}
var p1=new Person("vigneshwar","23-03-1996",27,"male","fsd","3/5 krms garden sulur");
var p2=new Person("viswanathan","15-07-1994",28,"male","backend","3/5 krms garden sulur");
var p3=new Person("vishnu priya","24-04-1999",24,"female","house wife","3/5 krms garden sulur");
var p4=new Person("vishnu surya","21-07-1992",30,"female","software engineer","3/5 krms garden sulur");
console.log(p1,p2,p3,p4)


-------------------------------------------------------------------------
4)Class to calculate the uber price :

class Uber{
    constructor(kms,price){
      this.kms=kms;
      this.price=price;
    }
}
var ride1=new Uber(10,150);
var ride2=new Uber(11,165);
var ride3=new Uber(15,225);

console.log(ride1.price+ride2.price+ride3.price);
