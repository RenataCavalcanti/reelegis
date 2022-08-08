---
title: "Metodologia"
weight: 4
header_menu: true
---

Para chegar aos resultados obtidos nesta [Plataforma](https://reelegis-reelegis-plataforma-reelegis-app-vpxy3k.streamlitapp.com), ou seja, a tradução do conteúdo das ementas em áreas temáticas, utilizamos uma técnica de aprendizado de máquina. Através desta metodologia é permitido organizar, compreender e descobrir quais são os temas presentes em um conjunto de documentos, através das palavras nesse contido e assim classificar cada documento no tópico que é mais apropriado.

Uma forma de compreender melhor essa metodologia seria supondo que você tenha um conjunto de livros que nunca leu (os documentos) e apenas as informações presentes no sumário e no título (as palavras), e com isso deseja organizá-lo na sua estante por categorias (tópicos) que você deseja criar. Ao notar que palavras como “dragão”, “bruxos”, “magia”, “elfos”, “caminhantes brancos” indicam que os livros pertencem a categoria de literatura fantástica, já "cebola", "tomate", "macarrão" e "vinho" formam o grupo de livros sobre culinária, enquanto palavras como “democracia”, “nações”, “políticos” ou “coalizão” enquadram os livros na literatura sobre política.

No nosso caso, utilizamos as “palavras-chaves” presentes em cada proposta apresentada pelos deputados e deputadas federais entre 2019 e 18 de julho de 2022 (56ª Legislatura) para descobrir os temas que os legisladores brasileiros enfatizaram neste período. As propostas e demais informações sobre os parlamentares foram retiradas do site da Câmara de Deputados. O processamento foi feito através da linguagem *R* e utilizamos a modelagem do algoritmo *Structural Topic Model (STM)* para descobrir quais são os temas mais enfatizados nesses documentos.

O nosso modelo analisou 29.155 iniciativas e possui uma taxa de **79% de acerto** na tentativa de predizer se aquela determinada proposta corresponde ao tema encontrado.

Em caso de qualquer dúvida sobre a metodologia da plataforma, entre em contato conosco no e-mail {{<icon class="fa fa-envelope">}}&nbsp;[cpcex.lab@ufpe.br](mailto:cpcex.lab@ufpe.br).

Também sugerimos a pesquisa e leitura desses materiais:

- [Página Oficial do STM](http://www.structuraltopicmodel.com/)
- [Texto como Dado](https://www.anpocs.com/index.php/bib-pt/bib-86/11215-o-texto-como-dado-desafios-e-oportunidades-para-as-ciencias-sociais/file)
- [Quais políticas importam? Usando ênfases na agenda legislativa para mensurar saliência](https://www.scielo.br/j/rbcsoc/a/gM7mG35jtmMBr45CNkqZKYq/?format=pdf&lang=pt)
