# Projeto-Janeiro-Branco

## Projeto: "Vozes das Cores" - Desenvolvendo um Site com Python
O objetivo deste projeto é criar um site informativo sobre uma das campanhas "Cores do Mês" (O meu é Janeiro Branco para informações sobre saúde Mental). O estudante escolherá uma cor/causa e usará Python para gerar as páginas do site de forma automatizada. Ao final, o site será publicado gratuitamente na web usando o GitHub Pages.
Tecnologias Utilizadas:

Python: Para a lógica de "back-end" (geração do site).
HTML5: Para a estrutura do site.
CSS3: Para a estilização e design.
GitHub: Para controle de versão e publicação do site (GitHub Pages).

# Passo a Passo das Atividades: 
Aqui estão as fases do projeto, desde a concepção até a publicação.

## Fase 1: Pesquisa e Planejamento
Escolha a Cor/Causa: Pesquise sobre as campanhas "Cores do Mês" e escolha uma que você se identifique.(Janeiro Branco: Saúde Mental)

Defina o Conteúdo: Para a causa escolhida, estruture o conteúdo do seu site. Pense nas seguintes seções:

O que é a campanha?

Qual a importância da causa?

Dados e estatísticas relevantes.

Como ajudar ou se prevenir?

Links úteis e fontes.

Desenhe um Rascunho (Wireframe): Em um papel ou ferramenta online, desenhe a estrutura visual do seu site. Onde ficará o título? Onde o menu (se houver)? Onde o conteúdo principal? Isso guiará seu desenvolvimento HTML e CSS.

## Fase 2: Configuração do Ambiente de Desenvolvimento
Instale o Python: Caso não tenha, baixe e instale a versão mais recente do Python em seu computador a partir do site python.org.
Editor de Código: Utilize um editor como o VS Code, Sublime Text ou Atom para escrever seus códigos HTML, CSS e Python.
Estrutura de Pastas: Crie uma pasta principal para o seu projeto. Dentro dela, organize os arquivos da seguinte forma:
/projeto-cores/
### |-- gerador_site.py  :   Nosso script Python
### |-- template.html    :   O modelo base da nossa página
### |-- style.css        :   A folha de estilos
### |-- conteudo.txt     :   O texto que será inserido na página
### |-- index.html       :   O arquivo final que será gerado pelo Python

## Fase 3: Desenvolvimento Front-End (HTML e CSS)
Crie o Template HTML (template.html): Este arquivo será a base do seu site. Ele conterá a estrutura HTML padrão e marcadores especiais (como {{TITULO}} e {{CONTEUDO}}) que o Python substituirá pelo conteúdo real.
Estilize com CSS (style.css): Crie as regras de estilo para o seu site. Use a cor da campanha escolhida como cor principal do design. Defina fontes, cores de texto, espaçamentos, etc.

## Fase 4: Desenvolvimento "Back-End" (Script Python)
Crie o Gerador de Página (gerador_site.py): Este script é o coração do projeto. Sua função será:
Ler o conteúdo do arquivo template.html.
Ler o conteúdo do arquivo conteudo.txt.
Substituir os marcadores no template pelo conteúdo lido.
Salvar o resultado final como um novo arquivo, o index.html.


Nota sobre o Google Colaboratory: Você pode desenvolver e testar o seu script Python (gerador_site.py) diretamente no Google Colab. Ele é excelente para experimentar a lógica de manipulação de arquivos e texto. No entanto, para desenvolver o projeto web completo (editando HTML, CSS e rodando o script para gerar o index.html), o ideal é trabalhar no seu computador local com um editor de código. O Colab serve como uma ótima ferramenta de apoio para a parte de Python.

# Modelo Completo: "Janeiro Branco - Saúde Mental"

 ## 1. Estrutura de Arquivos:
/Janeiro-Branco/

|-- gerador_site.py

|-- template.html

|-- style.css

|-- conteudo.txt

## 2. Código do template.html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
    </head>
<body>

    <header>
        </header>

    <nav>
        </nav>

    <main>
        <section>
            </section>

        <section>
            </section>
        </main>

    <footer>
        </footer>

</body>
</html>

 ## 3. Código do style.css:

   abra a pasta Janeiro-Branco > entre no arquivo "teste1css.css"

 ## 4. Conteúdo (conteudo.txt)

Vozes das Cores
Um convite à Saúde Mental e Emocional

Menu de Navegação
Campanha

Sobre

Importância

Cor e Causa

Poder da mente

Como se Cuidar

Referências

O Que é a Campanha Janeiro Branco?
A campanha Janeiro Branco é um movimento dedicado à conscientização sobre a importância da saúde mental e emocional. Ela busca prevenir doenças como ansiedade, depressão e pânico, que podem ser causadas pelo estresse, além de abordar outros transtornos de humor como esquizofrenia e transtorno bipolar.

Sobre o Projeto "Vozes das Cores"
Oi, sou André, um aluno do TDS, e o projeto Vozes das Cores tem como objetivo mostrar o significado das cores em cada mês do ano. Escolhi Janeiro, e sua cor é Branca, que significa saúde mental. Quero mostrar, com um pouco de história e ciência, a importância e a força que a mente tem sobre o corpo e algumas formas de prevenções.

Qual a Importância da Causa?
A campanha é crucial para alertar a população sobre a necessidade de cuidar do bem-estar psicológico. O mês de janeiro foi escolhido por ser um período simbólico, no qual as pessoas tendem a refletir sobre suas vidas e emoções, como se tivessem uma "folha em branco" para recomeçar.

Cor e Causa
A cor da campanha é o branco, simbolizando a "folha ou tela em branco" para que as pessoas possam reescrever suas histórias e focar na saúde mental. A causa principal é a conscientização e prevenção de doenças relacionadas ao estresse e saúde mental.

Caso 1
Jesus se dirige à mulher que sofria de uma hemorragia crônica por doze anos e que, desesperada, tocou em suas vestes, crendo firmemente que seria curada. Suas palavras são claras e poderosas: "Filha, a tua fé te salvou; vai em paz e sê curada deste teu mal."
Como a neurociencia explica esse fato de aproximadamente 2000 anos atras?
"Tua fé te curou." A ciência provou: crenças mudam sua biologia. Pensamento vira hormônio. Emoção vira doença ... ou cura. Jesus entendia o que você ainda está ignorando: a cura começa dentro.
O poder da mente sobre o corpo não é misticismo, é ciência. Seus pensamentos e emoções são químicos que ativam ou desativam genes, que constroem ou destroem sua saúde. A fé, nesse contexto, é a certeza de que a mudança é possível, e seu corpo responde a isso.

Caso 2
Em 1964, Angela Cavallo, nos Estados Unidos, tornou-se famosa por levantar um carro para salvar seu filho, Tony, que ficou preso embaixo do veículo após um acidente. Ela ouviu o estrondo e correu para ajudar, encontrando o filho preso por um dos para-lamas traseiros. Sem pensar nas limitações, Angela levantou o carro com as próprias mãos, permitindo que os vizinhos libertassem Tony. Este ato heroico demonstrou a força que uma mãe pode atingir em situações de perigo.
Nessa situação, o pensamento "tenho que salvar meu filho" impulsionou Angela a levantar o carro, que pesa cerca de 1.500 quilos. Em comparação, o recorde mundial de levantamento de peso (em categorias como powerlifting, que envolvem levantamento terra, agachamento e supino) para homens é de 501 kg no levantamento terra (Hafthor Bjornsson, embora haja controvérsias sobre o recorde fora de competição, e Benedikt Magnússon com 460.4 kg em competição) e, para mulheres, o recorde mundial no levantamento terra é de 305 kg (Becca Swanson).

Poder da mente
Em ambos os Casos acima, o ponto central é a quebra de barreiras. Seja pela ativação de mecanismos de sobrevivência ou pela força da crença espiritual, a mente se mostra capaz de superar limites físicos e emocionais, redefinindo o que consideramos possível. É uma prova inspiradora de que, em momentos de grande necessidade ou fé profunda, a mente humana detém um poder imenso, capaz de impulsionar atos de heroísmo e de manifestar o impossível.

Como se Prevenir e Cuidar da Saúde Mental?
Cautela com Expectativas: Estabeleça metas realistas e divida-as em etapas para evitar frustrações.

Auto-observação: Pratique a auto-observação diária com generosidade, reconhecendo suas qualidades e habilidades para lidar com desafios.

Atividades Satisfatórias: Invista em hobbies, esportes, atividades físicas e momentos de lazer que promovam o bem-estar.

Bons Hábitos: Adote uma alimentação saudável e priorize a qualidade do sono, criando uma rotina para dormir.

Consciência Sentimental: Identifique suas emoções e pensamentos para agir de forma mais consciente.

Atenção ao Presente: Concentre-se no que está sob seu controle no momento presente para reduzir a angústia.

Busque Ajuda: Reconhecer o sofrimento emocional é o primeiro passo para procurar apoio terapêutico e melhorar sua qualidade de vida.

Exposição ao Sol: A exposição ao sol é essencial para a nossa saúde física e mental. A luz solar desempenha um papel crucial na regulação dos neurotransmissores. (Saiba mais)

Dados e Referências
Impacto Geral: Houve um aumento significativo nos quadros de ansiedade e depressão após o início da pandemia de COVID-19. Estima-se que transtornos depressivos e ansiosos tiveram um aumento global de 25% com a pandemia. Saiba mais

Profissionais de Enfermagem: Uma sondagem realizada pelo Coren-SP (Conselho Regional de Enfermagem de São Paulo) em setembro de 2021 revelou que 62% dos profissionais de enfermagem afirmaram ter desenvolvido sofrimento mental durante a pandemia. Saiba mais

Agravamento de Quadros Psiquiátricos: Uma pesquisa da Associação Brasileira de Psiquiatria (ABP) indicou que 47,9% dos psiquiatras entrevistados notaram um aumento nos atendimentos após o início da pandemia, e 89,2% relataram o agravamento de quadros psiquiátricos em pacientes. Saiba mais

"Saúde Mental em Dados" do Ministério da Saúde: O Ministério da Saúde publica periodicamente o "Saúde Mental em Dados". A "Edição nº 13" de Fevereiro de 2025 é a mais recente disponível e deve conter informações abrangentes sobre o período solicitado. Saiba mais

história biblica: historia completa do video acima

história Angela Cavallo: R7 Noticias
Esta página foi compilada com base em informações de domínio público sobre a campanha Janeiro Branco. Para dados oficiais e mais detalhes, recomendamos a consulta de fontes governamentais e de saúde.
Para mais informações, você pode consultar a notícia completa no site oficial do INSS: Janeiro Branco: mês de conscientização pela saúde mental e emocional.

Lembre-se: Cuidar da mente é cuidar da vida.
Feito por: André Luis de Sousa Rodrigues
© 2025 Projeto Vozes das Cores. Todos os direitos reservados.

# Script Python (gerador_site.py)
Abre e lê o arquivo de template
with open('template.html', 'r', encoding='utf-8') as file:
    template = file.read()

Abre e lê o arquivo de conteúdo
with open('conteudo.txt', 'r', encoding='utf-8') as file:
    conteudo = file.read()
    
Define os valores para substituir no template
titulo_pagina = "Janeiro-Branco - Saúde Mental"
titulo_cabecalho = "Saúde Mental - informes e prevençao"

Substitui os marcadores pelos conteúdos
html_final = template.replace('{{TITULO_PAGINA}}', titulo_pagina)
html_final = html_final.replace('{{TITULO_CABECALHO}}', titulo_cabecalho)
html_final = html_final.replace('{{CONTEUDO}}', conteudo)

Cria e escreve o arquivo final index.html
with open('index.html', 'w', encoding='utf-8') as file:
    file.write(html_final)

print("Site gerado com sucesso! Abra o arquivo 'index.html' no seu navegador.")

# Fase Final: Publicando seu Site com GitHub Pages
Agora que seu site está pronto, vamos publicá-lo na internet para que todos possam ver.

## Crie uma Conta no GitHub: Se ainda não tiver, crie uma conta em github.com.

Crie um Novo Repositório:
Clique em "New" (Novo) na sua página do GitHub.
Dê um nome ao seu repositório (ex: projeto-março-lilas).
Marque a opção "Public" (Público).
Clique em "Create repository".

Envie seus Arquivos:
Dentro do seu novo repositório, clique em "Add file" > "Upload files".
Arraste os arquivos index.html e style.css para a área de upload. Atenção: Você só precisa enviar esses dois arquivos, pois o index.html já contém tudo.
Clique em "Commit changes".

Ative o GitHub Pages:
No seu repositório, clique na aba "Settings" (Configurações).
No menu lateral esquerdo, clique em "Pages" (Páginas).
Na seção "Build and deployment", em "Source", selecione "Deploy from a branch".
Na seção "Branch", certifique-se de que o ramo selecionado é o main (ou master) e a pasta é a /root.
Clique em "Save" (Salvar).

Acesse seu Site!
Após alguns minutos, o GitHub publicará seu site. Um link aparecerá no topo da seção do GitHub Pages, no formato: https://seu-usuario.github.io/nome-do-repositorio/
