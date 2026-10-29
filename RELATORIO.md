Ao enviar o código correto a pipeline executou todas as suas etapas com sucesso.
Quando provoquei a falha, a pipe ficou vermelha. O Github actions fornece os passos e consegui identificar exatamente onde o problema estava.
Após identificar o erro e corrigi-lo, dei push e a pipe voltou a ficar verde.
O benefício mais notório é termos um controle de condições que a aplicação deve respeitar para que sejam feitos commits. Isso ajuda a evitar que alguns bugs cheguem ao usuário.
Utilizei o flake8 para conferir a qualidade do código fornecido. Ele só acusou a falta de uma nova linha vazia que o Python exige.
