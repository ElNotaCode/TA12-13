# TA12-13
TA12 en brach main TA13 en branch ta13
![imagen](https://user-images.githubusercontent.com/19403472/164549427-5fa83651-d3d8-4ea6-9f03-e3037f1e5e55.png)
ATLETA(N_Dorsal(PK),Nombre,Altura,N_Dorsal_Relevo(FK))

![imagen](https://user-images.githubusercontent.com/19403472/164550887-1ba92df3-283a-4d76-80d6-8c7e7801f8bd.png)
ELEMENTO(Id_elemento(PK),Nombre_elemento,Peso_atomico,Simbolo,N_atomico)
COMPUESTO(Id_compuesto(PK),Nombre_compuesto)
GASEOSO(Id_compuesto(PK)(FK),Coef_expan,Temp_lie)
LIQUIDO(Id_compuesto(PK)(FK),Densidad,Temp_evap)
SOLIDO(Id_compuesto(PK)(FK),Color,Olor,Dureza)
COMPUESTO_POR(Id_compuesto(PK),Proporcion,Id_elemento(FK),Id_compuesto(FK))
