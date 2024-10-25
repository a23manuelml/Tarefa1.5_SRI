## Tarefa 1.5 - Subdominios

1. Instala no equipo lukeskywalker un subdominio hamado "mestre", e dentro del os rexistros 
    - A, kitfisto 192.168.20.212
    - A, macewindu 192.168.20.213.

    Captura a zonas, e un cliente resolvendo un rexistro A do dominio e do subdominio contra lukeskywalker

**SOLUCION:**

- Creamos o subdominio "mestre" na zona directa do servidor Lukeskywalker

    ![imaxe1](imaxes/solapt1.1.png)

- Engadimos os rexistros A dentro do subsominio mestre:

    ![imaxe2](imaxes/solapt1.2.png)

- Realizamos a comprobación:

    ![imaxe3](imaxes/solapt1.3.png)

    ![imaxe4](imaxes/solapt1.4.png)

2. Instala no equipo hansolo (Windows 2012) un subdominio delegado de "academia.jedi" chamado consello. . Engade nel os rexistros:
    - A, yaddle 192.168.20.215
    - A, yaraelpoof 192.168.20.216

    Captura as dúas zonas, e un cliente resolvendo un rexistro  A do dominio e do subdominio contra hansolo e lukeskywalker

**SOLUCION:**

- Delegar o subdominio consello.academia.jedi a hansolo:

    ![imaxe5](imaxes/solapt2.1.png)

- Creamos o dubdominio consello no servidor hansolo:

    ![imaxe6](imaxes/solapt2.2.png)

- Realizamos comprobación:

    ![imaxe7](imaxes/solapt2.3.png)

3. Instala no equipo darthvader un subdominio chamado antigarepublica, e nel os rexistros:
    - A, xendor 192.168.20.222
    - A, ardenlyn 192.168.20.223.

    Captura as dúas zonas, e un cliente resolvendo un rexistro  A do dominio e do subdominio contra darthvader

**SOLUCION**

- Captura da zona:

    ![imaxe8](imaxes/solapt3.1.png)

- Comprobación:

    ![imaxe9](imaxes/solapt3.2.png)

4. Instala no equipo leia (Debian/Ubuntu Server) un subdominio delegado de "starwars.lan" chamado imperio. Engade nel os rexistros:
    - A, tsuichoi 192.168.20.225
    - A, bultarswan 192.168.20.226.

    Captura as dúas zonas, e un cliente resolvendo un rexistro  A do dominio e do subdominio contra leia e darthvader

**SOLUCION**

- Fichero db.starwars.lan:

    ![imaxe10](imaxes/solapt4.1.png)

- Ficheiro named.conf.local do servidor leia:

    ![imaxe11](imaxes/solapt4.2.png)

- Ficheiro db.imperio.starwars.lan do servidor leia:

    ![imaxe12](imaxes/solapt4.3.png)
    
- Comprobación:

    - Leia:

        ![imaxe13](imaxes/solapt4.4.png)
    
    - Darthvader:

        ![imaxe14](imaxes/solapt4.5.png)
        
        ![imaxe15](imaxes/solapt4.6.png)