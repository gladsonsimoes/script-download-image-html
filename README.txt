Como funciona este script para fazer download de imagem dos links de atributo 'linkimg'

neste arquivo  tem dois scripts um para pegar os links do atributo linkimg e outro para transforma as imagens em pdf
caso seja varios imagens como livro por exemplo


1. copie o html do site com vários links de imagens e coloque o arquivo .html, 
 ele puxar no html somente links dentro do atributo 'linkimg'

2. clique com o lado direto do mouse no script 'extrair_link.ps1' , e clique na opção 'Executar com o Powershell' , após ter feito isso o script vai copiar todos os link e em seguida vai baixar as imagens com númeração

3. as imagens foram para a pasta downloaded_images , mas caso queira transformar em pdf clique com a lado direito 
do mouse no script 'image-merged-pdf.ps1' , após isso ele ai criar um arquivo pdf com o nome de 'output.pf' , este 
é o pdf com as imagens baixadas

4. após o uso recomendo que retire ou apague as imagens da pasta 'downloaded_images' , e também retire o arquivo 'output.pdf' , porque se caso fizer outro site vai substituir pelo atual.