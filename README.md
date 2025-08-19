# Criação do projeto
basta executar os seguintes comandos
<img width="864" height="236" alt="Captura de tela 2025-08-19 153753" src="https://github.com/user-attachments/assets/3b6925bb-a914-46a9-8224-782e648b92f0" />
lembre-se que estamos usando o Xampp por lembre de dar start no apache e MYSQL
<img width="656" height="420" alt="Captura de tela 2025-08-19 160517" src="https://github.com/user-attachments/assets/4cfd5be6-8391-42dc-b3fa-394dd63a5996" />
# Migrations
precisamos primeiro conectar o banco de dados através do arquivo .env
<img width="233" height="134" alt="Captura de tela 2025-08-19 160751" src="https://github.com/user-attachments/assets/d61c597f-a019-4893-bb76-d0310ffa3fd6" />
certifique-se de ter já criado o banco de dados no phpMyAdmin
<img width="1092" height="459" alt="image" src="https://github.com/user-attachments/assets/fe4c9efa-0d40-40a4-8466-bc02ff6516eb" />
com isso feito executaremos em um terminal o seguinte comando
<img width="989" height="233" alt="Captura de tela 2025-08-19 154130" src="https://github.com/user-attachments/assets/a987bd56-e1b8-4612-aa39-29e688375d26" />
agora um arquivo foi criado na pasta ...database/migrations com o mesmo nome declarado, vamos alterar a função "up()" desse arquivo
<img width="505" height="215" alt="Captura de tela 2025-08-19 154415" src="https://github.com/user-attachments/assets/fbfe00f6-ad2b-45fc-b778-1ea57f96d54f" />
mais uma vez vamos repetir o processo para a tabela estoque
<img width="974" height="137" alt="Captura de tela 2025-08-19 154521" src="https://github.com/user-attachments/assets/c2727cf6-d0eb-428c-a7fa-1444f6dec759" />
<img width="827" height="333" alt="image" src="https://github.com/user-attachments/assets/79b50100-f1c5-4feb-98c7-b281fabd3f02" />
agora vamos alterar a tabela cadastro, vamos executar o comando
<img width="1189" height="129" alt="Captura de tela 2025-08-19 154831" src="https://github.com/user-attachments/assets/024f235f-13ff-4b6e-b3cb-22f97a2a54a3" />
e alteramos o arquivo gerado na mesma pasta das demais
<img width="498" height="168" alt="image" src="https://github.com/user-attachments/assets/cc4afcb5-ebc2-46f2-914d-8e7a43bda6cc" />
por ultimo executamos as migrations
<img width="1097" height="313" alt="Captura de tela 2025-08-19 155652" src="https://github.com/user-attachments/assets/d2017e6c-a735-464b-bd47-0f602932f516" />
o resultado deve aparecer em seu phpMyAdmin
<img width="1596" height="237" alt="image" src="https://github.com/user-attachments/assets/78a82368-8f97-41b9-8535-072c682acc91" />
<img width="701" height="52" alt="Captura de tela 2025-08-19 155725" src="https://github.com/user-attachments/assets/8cb77466-4313-4e49-9de7-33898f9bdf25" />
<img width="545" height="38" alt="Captura de tela 2025-08-19 155731" src="https://github.com/user-attachments/assets/8494567d-05a0-459a-b88a-3f378f7ee2cf" />
