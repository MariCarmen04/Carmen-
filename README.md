# Carmen-
Planetas 
$ include˂stdio.h˃
·include˂conio.h˃
·include˂math.h˃
·include˂string.h˃

$ Int planeta, Temp
$ char Nombre;
$ float Radio=0,MasaP=0,v2,MasaE1=0,MasaE2=0,MasaE3=0,Vrms=0;
$ float  G=6.67e-11;
$ float k=1.349e-23;
$ float Hidrogeno=6.67e-27,Oxigeno=2.65e-26,Helio=6.64e-27,Nitrógeno=2.32e-26,Carbono=1.99e-26,Azufre=5.32e-26;
main()
{
$ Print (“Elije un planeta  \n1-Sol\n2-Mercurio\n3-Venus\n4-Tierra\n5-Luna\n6-Marte\n7-Jupiter\n8-Saturno\n9-Titan\n10-Urano\n11-Neptuno\n12-Pluton\nscanf(“%d”,&planeta);
//Velocidad de Escape 
//v2=sqrt((2*G*masa/Radio);

//Velocidad Molecular 
//Vrms=sqrt((3*K*Temp)/MasaE);
Switch(planeta)
{

# Case 1
$ Print (“\ Sol\n”);
Temp=5780;
MasaP=1.989e+30;
Radio=7.0e+8;
MasaE1=Hidrogeno;
MasaE2=Helio;
v2=sqrt((2*G*MasaP)/Radio);
printf(“la velocidad de Escape es de: %.4f/n”,Vrms2);
printf(“\nLa atmosfera del Sol se compone de gases: \n”);
Vrms2=sqrt((3*K*Temp)/MasaE1);
printf(“\nHidrogeno:\n”);
printf(“La velocidad Molecular es de: %.4f \n”,Vrms2);
break;

case 2
printf(“\n**Mercurio**\n”);
Temp=400;
MasaP=3.285e+23;
Radio=2.4e+6;
v2=sqr((2*G*MasaP)/Radio);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Mercurio es despreciable”);
break;

case 3:
printf(“\n````Venus````\n”);
Temp=290;
MasaP=4.867e+24;
Radio=6.1e+6;
MasaE1=Nitrógeno;
v2=sqrt((2*G*MasaP)/Radio); 
Vrms1=sqrt((3*K*Temp)/MasaE1);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de venus se compone de gases:\n”);
printf(“\nNitrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f/n”,Vrms1);
printf(“Dióxido de Carbono\n”)
printf(“Dioxido de Azufre”);
break;

Case 4
Printf(“\n`````Tierra``````\n”);
Temp=250;
MasaP=5.922e+24;
Radio=6.4e+6;
MasaE1=Nitrógeno;
MasaE2=Oxigeno;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
Vrms2=sqrt((3*K*Temp)/MasaE2);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de la Tierra se compone de los gases: \n”);
printf(“\Nitrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Oxigeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms2);
printf(“Agua”);
break;

Case 5:
Printf(“\n`````Luna``````\n”);
Temp=250;
MasaP=7.34e+22;
Radio=1.7e+6;
v2=sqrt((2*G*MasaP)/Radio);
printf(“La velocidad de Escape es de: %.4f\n,v2);
printf(“La atmosfera de la Luna no se compone de gases”);
break;

case 6:
Printf(“\n`````Marte``````\n”);
Temp=200;
MasaP=6.39e+6;
Radio=6.4e+6;
MasaE1=Nitrógeno;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Marte se compone de los gases: \n”);
printf(“\Nitrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Dioxido de Carbono”);
break;

case 7:
Printf(“\n`````Jupiter ``````\n”);
Temp=110;
MasaP=1.898e+27;
Radio=7.1e+7;
MasaE1=Nitrógeno;
MasaE2=Helio;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
Vrms2=sqrt((3*K*Temp)/MasaE2);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Jupiter se compone de los gases: \n”);
printf(“\Hidrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Helio:\n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms2);
printf(“Metano”);
break;

case 8:
Printf(“\n`````Saturno``````\n”);
Temp=80;
MasaP=5.683e+26;
Radio=6.0e+7;
MasaE1=Hidrogeno;
MasaE2=Helio;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
Vrms2=sqrt((3*K*Temp)/MasaE2);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Saturno se compone de los gases: \n”);
printf(“\nHidrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Helio:\n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms2);
printf(“Metano”);
break;

case 9:
Printf(“\n`````Titan``````\n”);
Temp=80;
MasaP=1.898e+27;
Radio=2.6e+6;
MasaE1=Nitrógeno;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de la Titan se compone de los gases: \n”);
printf(“\nNitrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Metano”);
break;

case 10
Printf(“\n`````Urano``````\n”);
Temp=55;
MasaP=1.345e+23;
Radio=2.5e+7;
MasaE1=Hidrogeno;
MasaE2=Helio;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
Vrms2=sqrt((3*K*Temp)/MasaE2);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Urano se compone de los gases: \n”);
printf(“\nHidrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Helio:\n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms2);
break;
 
case 11:
Printf(“\n`````Neptuno``````\n”);
Temp=45;
MasaP=1.024e+26;
Radio=2.2e+7;
MasaE1=Hidrogeno;
MasaE2=Helio;
v2=sqrt((2*G*MasaP)/Radio);
Vrms1=sqrt((3*K*Temp)/MasaE1);
Vrms2=sqrt((3*K*Temp)/MasaE2);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Nepturno se compone de los gases: \n”);
printf(“\nHidrogeno: \n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms1);
printf(“Helio:\n”);
printf(“La velocidad Molecular es de: %.4f\n”,Vrms2);
break;

case 12:
Printf(“\n`````Pluton``````\n”);
Temp=40;
MasaP=1.25e+22;
Radio=1.4e+6;
v2=sqrt((2*G*MasaP)/Radio);
printf(“La velocidad de Escape es de: %.4f\n”,v2);
printf(“\nLa atmosfera de Pluton se compone de los gases: \n”);
break;

} 
getch();
}
