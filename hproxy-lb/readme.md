/usr/share/nginx/html
/etc/nginx/nginx.conf

docker-compose up -d --scale web=3
#Erros conhecidos:
    Missing LF on last line, file might have been truncated at position
Quando configuramos um arquivo, no unix ele deixa uma 'sujeira' no final da linha, como um %. É necessario remove-lo.