# Web Scraping com Beaultifulsoap
Raspando o site letras.com.br em busca de letras musicais.
-----
### O que é
Este script captura todas os links de uma banda, grupo ou artista a partir da página www.letras.com.br/{banda}, em seguida, ele acessa cada um dos links e captura todas as músicas. O Tratamento começa com o método "punctuation" que remove todos os caracteres especiais do texto. Por fim, usando NLTK, este script remove todas as stopwords e retorna uma string contida de todas as palavras restantes.
### Finalidade
Com este script é possível capturar grande massa de palavras a fim de trabalhar com análise de sentimentos ou simplesmente criar uma nuvem de tags.
### Como usar
Clone, copie e cole ou faça download do arquivo web-scraping-beautifulsoap.py, em seguida digite em um Terminal **python3 web-scraping-beautifulsoap.py [nome da banda ou grupo músical]**. Veja os exemplos a seguir:

```bash
# exemplo para capturar todas as letras da banda Skank
python3 web-scraping-beautifulsoap.py skank

# exemplo para capturar todas as letras da banda Pato-Fu
python3 web-scraping-beautifulsoap.py pato-fu
```
Se acaso você ficar na dúvida de como formar o argumento da linha de comando, ou seja, como escrever o nome de sua banda ou grupo musical predileto, basta ir ao site www.letras.com.br e entrar no *profile* da sua banda ou grupo musical predileto.
<br><img src='url.png' width=700><br>
Copie apenas o nome e cole no Terminal junto do restante do código e pressione ENTER para confirmar. O processo de raspagem pode demorar um pouco a depender da sua velocidade de conexão com a internet. 
