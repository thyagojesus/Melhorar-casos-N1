# Melhoria de Descrição de Casos N1 com Google Gemini API

Este projeto utiliza a API do Google Gemini para aprimorar a descrição de casos N1, gerando textos mais completos, precisos e informativos para facilitar a análise e resolução de problemas.

## Funcionalidades:

* **Análise e Geração de Texto:** Emprega o modelo de linguagem "gemini-1.5-pro-latest" para analisar descrições iniciais e gerar textos aprimorados.
* **Orientações Personalizadas:** Utiliza instruções específicas para garantir que as descrições geradas incluam informações relevantes como problema relatado, procedimentos executados, evidências, soluções e próximas etapas.
* **Formatação Estruturada:** Mantém a estrutura dos casos N1, incluindo seções para problema, procedimento, evidências e solução, garantindo clareza e organização.
* **Interface Simples:** Permite inserir o texto do chamado a ser corrigido diretamente no código.

## Como Usar:

**Para utilizá-lo, insira o texto do chamado a ser corrigido no input. 
**mantendo a estrutura original com os campos "Problema relatado", "Procedimento Executado", "Evidências" e "Solução".**

**Exemplo de entrada:**
* ```
* **Problema relatado: Loja informa que todos os celulares estão com problema ao finalizar a venda, não finaliza 
* **Procedimento Executado: solicitado para atualizar versão do linxmobile pelo linx updater, ler o qrcode no PDV1 feito acesso ao celular ID ID0QPE Solicitado teste de venda, venda finalizada normalmente
* **Evidências: 
* **Solução: resolveu com a atualizao
* ** ```


## Observações:

* Este projeto requer uma chave API válida do Google Gemini.
* O modelo de linguagem "gemini-1.5-pro-latest" pode estar sujeito a alterações ou limitações de acesso.
* A qualidade da descrição gerada depende da qualidade da descrição inicial e das orientações fornecidas.

## Próximos Passos:

* Implementar uma interface de usuário mais amigável.
* Permitir a seleção de diferentes modelos de linguagem.
* Integrar com sistemas de gestão de casos N1.

## Contribuições:

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, enviar pull requests ou sugerir novos recursos. 
