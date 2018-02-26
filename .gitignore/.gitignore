#!/bin/bash
clear

NOME(){
	read -p "Digite o seu nome: " nome	
	echo $nome | grep -E '^[0-9.-\=_,><?:;!@#$%�&*()_+\""][ ]$'
	if [ $? == 1 ]; then
		clear
		echo "Nome esta correto"
		sleep 1
		clear
		EMAIl
	else
		echo "Nome errado"
		echo "Digite novamente:"
		sleep 1
		clear
		NOME
	fi
}

EMAIL(){
	read -p "Digite o seu email: " email	
	echo $email | grep -E '^(A-Za-z0-9\.\_\-)+[@][A-Za-z0-9]+(\.com|\.br)|(\.com\.br)$'
	if [ $? == 1 ]; then
		clear
		echo "Email esta certo"
		sleep 1
		clear
		TELEFONE
	else
		echo "Email errado"
		echo "Digite novamente:"
		sleep 1
		clear
		EMAIL
	fi
}

TELEFONE(){
	echo "Formato do telefone: (XX)XXXX-XXXX"
	read -p "Digite o seu telefone: " telefone	
	echo $telefone | grep -E '^[(][0-9]{2}[)][0-9]{4}+-[0-9]{4}$'
	if [ $? == 0 ]; then
		clear
		echo "Telefone esta certo"
		sleep 3
		clear
		RG
	else
		echo "Telefone errado"
		echo "Digite novamente:"
		sleep 3
		clear
		TELEFONE
	fi
}


RG(){
	echo "Formato do documento: XX.XXX.XXX-X"
	read -p "Digite o seu rg: " rg	
	echo $rg | grep -E '^[(][0-9]{2}[)][0-9]{4}+-[0-9]{4}$'
	if [ $? == 0 ]; then
		clear
		echo "RG esta certo"
		sleep 3
		clear
		CPF
	else
		echo "RG errado"
		echo "Digite novamente:"
		sleep 3
		clear
		RG
	fi
}

CPF(){
	echo "Formato do documento: 000.000.000-00"
	read -p "Digite o seu cpf " cpf	
	echo $cpf | grep -E '^[0-9]{3}[.][0-9]{3}[.][0-9]{3}[-][0-9]{2}$'
	if [ $? == 0 ]; then
		clear
		echo "CPF esta certo!"
		sleep 2
		clear
		NASC
	else
		echo "CPF errado"
		echo "Digite novamente:"
		sleep 2
		clear
		CPF
	fi
}

NASC(){
	echo "Formato da data: 00/00/0000"
	read -p "Digite a data de seu nascimento " nasc	
	echo $nasc | grep -E '^[0-9]{2}\/[0-9]{2}\/[0-9]{4}$'
	if [ $? == 0 ]; then
		clear
		echo "A data est� certa"
		sleep 1
		clear
		NASC
	else
		echo "A data errada"
		echo "Digite novamente:"
		sleep 1
		clear
		CPF
	fi
}

IP(){
        read -p "Digite o seu ip: " ip
        		
		echo $ip | grep -E '^([0-9]|[1-9][0-9]|1[0-9]{2}|2[0-4][0-9]|25[0-5])(\.([0-9]|[1-9][0-9]|1[0-9]{2}|2[0-4][0-9]|25[0-5])){3}$'
		
		if [ $? == 0 ]; then
		clear
		echo "O ip ta certo!"
		sleep 1
		clear
		MASK
	else
		echo "O ip ta errado"
		echo "Digite novamente:"
		sleep 1
		clear
		IP
	fi
    }

MASK(){
        read -p "Digite a sua m�scara de rede: " mask
        		
		echo $mask | grep -E '^([0-9]|[1-9][0-9]|1[0-9]{2}|2[0-4][0-9]|25[0-5])(\.([0-9]|[1-9][0-9]|1[0-9]{2}|2[0-4][0-9]|25[0-5])){3}$'
		
		if [ $? == 0 ]; then
		clear
		echo "A m�scara esta certa"
		sleep 1
		clear
		
	else
		echo "A m�scara errada"
		echo "Digite novamente:"
		sleep 1
		clear
		MASK
	fi
  
}
NOME

