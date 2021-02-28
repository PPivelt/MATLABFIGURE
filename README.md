# MATLABFIGURE
clear
clc
x=[98,101,104,107,110,113,116]
y421=[795366.8	850859.4	898731.9	947693.7	998575.2	1049884.3	1103274.7]
y436=[767272.5	815085	861498.6	908936.7	957750.6	1007686.5	1059052.8]
y40=[731814	781997.1	826098.2	870994.1	917332.5	964648.4	1013144.3]
plot(x,y421,'Marker','o','MarkerSize',5,'Color','b','LineWidth',1)%circle
hold on
plot(x,y436,'Marker','d','MarkerSize',5,'Color','r','LineWidth',1)%diamond
hold on
plot(x,y40,'Marker','s','MarkerSize',7,'Color','m','LineWidth',1)%diamond
hold on
xtest1=103.3
ytest1=0.89*10^6
plot(xtest1,ytest1,'Marker','*','MarkerSize',7,'Color','k')
hold on
xtest2=102.9
ytest2=0.86*10^6
plot(xtest2,ytest2,'Marker','*','MarkerSize',7,'Color','k')
xtest3=108.2
ytest3=0.895*10^6
plot(xtest3,ytest3,'Marker','*','MarkerSize',7,'Color','k')
xtest4=107
ytest4=0.875*10^6
plot(xtest4,ytest4,'Marker','*','MarkerSize',7,'Color','k')
set(gca,'FontName','Times New Roman', 'FontSize',13)
set(gca,'XLim',[98 116])
xlabel('Flowrate(m^3/h)','FontName','Times New Roman', 'FontSize',16)
ylabel('Pressure Drop(Pa)','FontName','Times New Roman', 'FontSize',16 )
legend({'D42.1+F45','D42.85+F41','D43.6+F37'},...
'Location','southeast','NumColumns',1)

![压降随流量的变化关系1188-0127](https://user-images.githubusercontent.com/70458605/109407091-f3ae9d00-799f-11eb-998f-cecf31585ad2.png)
