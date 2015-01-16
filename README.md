# site_pdo

site simples desenvolvido em PHP com PDO 

finalidade: trabalhar com PDO

PDO (PHP Data Objects) é uma extensão que fornece uma interface padronizada para trabalhar com bancos de dados, 
cuja finalidade é abstrair a conexão e interações com os bancos, 
ou seja, independente do banco de dados que estiver sendo utilizado os métodos executados serão os mesmos,
mas isso não significa que seu sistema será portável entre diversos bancos de dados, 
por mais que o uso do PDO facilite a portabilidade, 
esta interface significa apenas que você se comunicará 
com qualquer banco de dados através de um determinado conjunto de métodos e classes.

O site está trazendo uma lista de cursos do database, e cadastrando usuários que tem interesse em fazer algum curso da lista.
conta também com uma arquivo fixture para carregar o database padrão e um arquivo config.php sendo incluido na classe PDO. 
