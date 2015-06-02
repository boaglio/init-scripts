# init-scripts
Server init scripts for Linux

## Tomcat 7

 _service tomcat7 [opcoes]_
 
```
 * Opcoes para subir:
 start ----------- inicia o Tomcat limpando todos os temporarios
  
 noclean-start --- inicia o Tomcat sem limpar arquivos temporarios
 nologs-start ---- inicia o Tomcat limpando todos temporarios e logs
 
 * Opcoes de restart:
 restart ---------- derruba e inicia o Tomcat limpando todos os temporarios
 noclean-restart -- derruba e inicia o Tomcat sem limpar arquivos temporarios
 nologs-restart --- derruba e inicia o Tomcat limpando todos temporarios e logs

 * Opcoes de derrubar:
 stop  - derruba o Tomcat

 * Outras:
 status  - mostra o processo e consumo do Tomcat
```
