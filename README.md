# applause
works worth applauding, every now


lambda usage sequence
(p1,p2,...)->{operation on p1,p2,.... might be a return statement too or a value}
// say you want to print certain fields in a customer object - Customer oldCust
so the method would look like:
void printCustDetails(Customer oldCust){
(oldCust)->{System.out.println(oldCust.getName()+" "+oldcust.getAddress());}
}
// say you want to compare 2 customers, use the same pattern - only difference is there are 2 parameters now
void compareCustAges(Customer newCus,Customer potentialCust){
(oldCust,newCust)->(oldCust.getAge()>potentialCust.getAge());
}
