# redes_Sistemas_Informaticos
LA EMPRESA ES PROZIS.SL
ESTA EMPRESA TENDRA DISTINTAS AREAS DE TRABAJO:

    -1ºDISEÑO DE ROPA
    -2ºDISEÑO DE DISPOSITIVOS ELECTRONICOS
    

LA PRIMERA RED SERÁ: AREA DE TRABAJO DE DISEÑO DE ROPA

    La red es la 192.168.1.0/24
    Se pone un servidor Web y  un servidor DNS.
    Las características de los objetos en la red son:
    
        PC0
            -IP 192.168.1.3
            -Mascara 255.255.255.0
            -dns server 192.168.1.100
        PC1
            -IP 192.168.1.4
            -Mascara 255.255.255.0
            -dns server 192.168.1.100
        PC2
            -IP 192.168.1.5
            -Mascara 255.255.255.0
            -dns server 192.168.1.100
            
        PC3
            -IP 192.168.1.6
            -Mascara 255.255.255.0
            -dns server 192.168.1.100    
        Web
            -IP 192.168.1.1
            -Mascara 255.255.255.0
        DNS
            -IP 192.168.1.100
            -Mascara 255.255.255.0
        
        EN ESTA RED ACCEDEREMOS AL LINK www.prozissl.com(pagina para diseño de ropa) la cual esta asignada en el DNS SERVER
        (IMPORTANTE: ACCEDER AL LINK DESDE ALGUN ORDENADOR: PCO-PC1-PC2-PC3)
    
LA SEGUNDA RED SERÁ:AREA DE TRABAJO DE DISEÑO DE DISPOSITIVOS ELECTRÓNICOS
    
    La red será de tipo DHCP.
    Se pone un Servidor DNS.
    Las características de los objetos en la red son:
    
    PC4
        -DHCP
    PC5
        -DHCP
    PC6
        -DHCP
    PC7
        -DHCP
        
    Se configura manualmente el servidor DHCP con la dirección 192.168.2.254
    Se asume que el gateway o la puerta de enlace para la red es 192.168.2.254 y que el servidor DNS es 192.168.2.100
    
     EN ESTA RED ACCEDEREMOS AL LINK 192.168.2.254(pagina para diseño de dispositivos electronicos) la cual esta asignada en el DNS          SERVER
        (IMPORTANTE: ACCEDER AL LINK DESDE ALGUN ORDENADOR: PC4-PC5-PC6-PC7)
    

