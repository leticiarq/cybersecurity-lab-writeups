# Password reset poisoning via middleware

## Informações

- **Plataforma:** PortSwigger Web Security Academy
- **Trilha:** Authentication vulnerabilities
- **Categoria:** Other authentication mechanisms
- **Dificuldade:** Practitioner
- **Status:** Não iniciado
- **Data de conclusão:** 
- **Laboratório:** [Acessar laboratório](https://portswigger.net/web-security/authentication/other-mechanisms/lab-password-reset-poisoning-via-middleware)

## Objetivo

Investigar como cabeçalhos processados por middleware podem alterar a geração de links de redefinição de senha.

## Conceitos estudados

- Password reset poisoning
- Host header
- Middleware
- Tokens de redefinição

## Ferramentas utilizadas

<!-- Liste somente as ferramentas e os recursos que você realmente utilizou. -->

- 
- 

## Reconhecimento e cenário

<!-- Descreva como o mecanismo de autenticação funciona e o que você observou antes da exploração. -->


## Análise da vulnerabilidade

<!-- Explique qual é a falha, onde ela acontece e por que o comportamento é inseguro. -->


## Metodologia e exploração

### 1. Identificação da requisição relevante

<!-- Descreva a ação feita no navegador e registre o método, endpoint e parâmetros importantes. Remova cookies e tokens desnecessários. -->

```http

```

### 2. Configuração do teste

<!-- Explique a configuração usada no Burp Suite ou em outra ferramenta. Inclua posições de payload, tipo de ataque, listas e filtros relevantes. -->


### 3. Análise dos resultados

<!-- Registre o indicador que diferenciou a resposta: mensagem, tamanho, status HTTP, tempo, redirecionamento ou outro sinal. -->


### 4. Validação

<!-- Explique como confirmou a vulnerabilidade e concluiu o laboratório. -->


## Evidências

| Evidência | Resultado observado |
|---|---|
| Requisição inicial |  |
| Resposta relevante |  |
| Indicador da vulnerabilidade |  |
| Validação final |  |

<!-- Adicione imagens à pasta images/ e substitua os exemplos abaixo pelos nomes reais. -->

<!-- ![Descrição da evidência](images/01-nome-da-imagem.png) -->

## Impacto

<!-- Explique o que um atacante poderia obter ou realizar ao explorar essa vulnerabilidade em uma aplicação real. -->


## Causa raiz

<!-- Identifique a decisão de implementação ou validação ausente que originou a falha. -->


## Correções recomendadas

<!-- Relacione cada correção à causa da vulnerabilidade. -->

- 
- 
- 

## O que aprendi

<!-- Escreva as conclusões com suas palavras: descoberta principal, dificuldade, recurso do Burp e aplicação futura. -->

- 
- 
- 

## Referências

- [Password reset poisoning via middleware — PortSwigger Web Security Academy](https://portswigger.net/web-security/authentication/other-mechanisms/lab-password-reset-poisoning-via-middleware)
- [Authentication vulnerabilities](https://portswigger.net/web-security/authentication)
