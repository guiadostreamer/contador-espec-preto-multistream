# Contador de Espectadores Guia Preto Multistream

Widget visual para exibir, em uma única barra, o total de espectadores e a audiência individual das plataformas conectadas ao Streamlabs.

Esta é a edição preta estática do contador: fundo preto sólido, contornos brancos e estrutura horizontal compacta. Ela foi criada para quem prefere um visual sóbrio, limpo e sem efeitos decorativos em movimento.

> **AVISO DE DIREITOS AUTORAIS E LICENÇA**  
> Este repositório é público para facilitar o acesso ao widget, mas o código **não está em domínio público** e **não possui licença para redistribuição**. O uso é gratuito somente nas condições descritas neste documento e no arquivo `LICENSE.txt`.

## Recursos

- Total automático de espectadores somando as plataformas exibidas.
- Contadores individuais para Twitch, YouTube, Facebook e Kick.
- Compatível com o widget **Contador de espectadores** do Streamlabs.
- Layout horizontal preto, compacto e discreto.
- Fundo preto sólido com bordas e divisórias brancas.
- Fundo externo transparente para integração com a cena.
- Indicador **AO VIVO** em destaque.
- Atualização automática do total de espectadores.
- Formatação numérica adaptada ao português do Brasil.
- Compatível com fontes de navegador do OBS Studio.

## Requisitos

- Uma conta no Streamlabs.
- As plataformas desejadas conectadas e autorizadas no Streamlabs.
- O widget **Contador de espectadores** com HTML/CSS personalizado habilitado.
- Uma fonte de navegador no OBS Studio ou em outro programa compatível.

> A leitura dos espectadores depende dos dados entregues pelo Streamlabs e pelas plataformas conectadas. Uma plataforma offline, desconectada ou com atualização atrasada pode exibir zero temporariamente.

## Instalação

1. Abra o painel do Streamlabs.
2. Entre em **Todos os widgets** e abra **Contador de espectadores**.
3. Ative **HTML/CSS personalizado**.
4. Substitua o conteúdo da aba **HTML** pelo conteúdo do arquivo HTML deste projeto.
5. Substitua o conteúdo da aba **CSS** pelo conteúdo do arquivo CSS deste projeto.
6. Substitua o conteúdo da aba **JS** pelo conteúdo do arquivo JavaScript deste projeto.
7. Marque as plataformas que deseja mostrar.
8. Defina a cor de fundo do widget como transparente.
9. Salve as configurações.
10. No OBS Studio, atualize a fonte de navegador do widget.

## Arquivos

- **HTML:** estrutura do contador e modelo usado pelo Streamlabs para criar cada plataforma.
- **CSS:** aparência preta estática, dimensões, contornos e transparência externa.
- **JS:** leitura, soma e atualização do total de espectadores.
- **LICENSE.txt:** condições completas para utilização do projeto.

## Licença de uso

Copyright © 2026 Leonardo — Guia do Streamer. Todos os direitos reservados.

### Você pode

- Usar gratuitamente o widget em suas próprias transmissões pessoais ou monetizadas.
- Personalizar cores, tamanhos, textos e aparência para uso próprio.
- Modificar o código para adequá-lo à sua própria transmissão.
- Exibir o widget em vídeos, lives, gravações e materiais que mostrem a sua transmissão.

### Você não pode

- Redistribuir, republicar ou disponibilizar o código original ou modificado, integralmente ou em partes substanciais.
- Criar repositórios espelho, páginas de download, pacotes, coleções ou arquivos alternativos contendo este projeto.
- Fazer reupload dos arquivos em sites, grupos, fóruns, redes sociais, vídeos ou outras plataformas.
- Vender, sublicenciar, alugar ou incluir este código em produtos, serviços, packs ou templates pagos ou gratuitos.
- Oferecer versões derivadas do widget para download ou distribuição.
- Remover ou alterar os avisos de autoria, licença ou identificação existentes nos arquivos.
- Apresentar o projeto, o layout ou o código como criação própria.
- Usar o nome **Guia do Streamer** de forma que sugira parceria, autorização ou endosso inexistente.

### Como compartilhar corretamente

Compartilhe somente o link da publicação ou do repositório oficial do **Guia do Streamer**. Não envie cópias dos arquivos e não crie links alternativos de download.

O acesso público ao repositório não concede permissão para revenda, redistribuição, reupload ou mudança de autoria. Qualquer uso que não esteja expressamente autorizado exige permissão prévia e escrita do responsável pelo projeto.

## Autoria e identificação

- **Projeto:** Contador de Espectadores Guia Preto Multistream
- **Edição:** preta estática com contornos brancos
- **Versão inicial:** 1.0.0
- **Identificador do projeto:** `GDS-VC-PRETO-260908-584217`
- **Direção criativa, conceito, personalização, testes e publicação:** Leonardo — Guia do Streamer
- **Desenvolvimento técnico:** realizado com auxílio de Inteligência Artificial

O histórico de commits, as tags, as releases, os arquivos originais e as datas deste repositório fazem parte do registro técnico de evolução do projeto.

## Limites da proteção

Estas regras protegem o código, os textos, a documentação e os elementos criativos específicos deste projeto. Elas não reivindicam exclusividade sobre a ideia genérica de um contador de espectadores, sobre recursos oferecidos pelo Streamlabs nem sobre implementações independentes que não copiem este material.

## Aviso de funcionamento

O widget é fornecido no estado em que se encontra, sem garantia de disponibilidade contínua. Mudanças realizadas pelo Streamlabs, pelas plataformas de transmissão ou pelo navegador integrado do OBS podem exigir atualizações futuras.

Streamlabs, Twitch, YouTube, Facebook, Kick e OBS são nomes e marcas pertencentes aos seus respectivos titulares. Este projeto é independente e não representa parceria ou endosso oficial dessas empresas.

## Créditos

Projeto criado para a comunidade do **Guia do Streamer**.

Se este widget ajudou sua transmissão, compartilhe o link oficial do projeto e preserve os créditos.
