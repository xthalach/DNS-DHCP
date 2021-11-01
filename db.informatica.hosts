;
; BIND data file for local loopback interface
;
$TTL	604800
informatica.com.	IN	SOA	informatica.com. root.informatica.com. (
			      2		; Serial
			 604800		; Refresh
			  86400		; Retry
			2419200		; Expire
			 604800 )	; Negative Cache TTL
;
informatica.com.	IN	NS	servidor-primari.informatica.com.
informatica.com.	IN	NS	servidor-secundari.informatica.com.
informatica.com.	IN	A	192.168.76.1
informatica.com.	IN	A	192.168.176.1
informatica.com.	IN	A	192.168.76.2
informatica.com.	IN	A	192.168.176.2
servidor-secundari	IN	A	192.168.176.2
servidor-secundari	IN	A	192.168.76.2
servidor-primari	IN	A	192.168.76.1
servidor-primari	IN	A	192.168.176.1
www			IN	CNAME	servidor-primari
