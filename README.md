class bank()
{
string name,code;
double year of estd;
float getRateOfInterest=1;
}
class bank1 extends bank()
{
string branch;
float getrateofinterest=5;
}
class bank2 extends bank()
{
float getrateofinterest=6;
}
class bank3 extends bank()
{float getrateofinterest=4;
}
bank1.name=SBI;
bank2.name=IOB;
bank3.name=BOI;
bank1.code=1;
bank2.code=2;
bank3.code=3;
system.out.println("bank1.getRateOfInterest"+bank1.getRateOfInterest);
system.out.println("bank2.getRateOfInterest"+bank2.getRateOfInterest);
system.out.println("bank3.getRateOfInterest"+bank3.getRateOfInterest);
}
