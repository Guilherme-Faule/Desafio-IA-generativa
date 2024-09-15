## Projeto desafio no Azure AI Studio ❣️
> <span style="color:red">**Orientações do copilot**</span>. Para começar um projeto, é geralmente mais prático iniciar pelo repositório local e depois conectá-lo ao GitHub. Aqui estão os passos básicos:

1. Criar um repositório local:
Crie uma pasta para o seu projeto.
Navegue até a pasta no terminal git bash ou no VS Code.
Execute: 
- [ ] 	__git init__
para inicializar um novo repositório Git.
- [ ] 	**git add ..** Adicione seus arquivos ao repositório
- [ ] 	**git commit -m "Primeiro commit"** Faça o primeiro commit 
2. Criar um repositório no GitHub:
Vá até o GitHub e crie um novo repositório.
Copie a URL do repositório recém-criado.
Conectar o repositório local ao GitHub:
No terminal, adicione o repositório remoto com 
- [ ] 	**git remote add origin [URL do repositório].**
3. Enviar suas alterações para o GitHub com 
- [ ] 	**git push -u origin main**
> Dessa forma, você pode trabalhar localmente e sincronizar suas alterações com o GitHub, aproveitando o melhor dos dois mundos. Se precisar de mais detalhes, posso te ajudar com tutoriais específicos ou comandos adicionais. 🚀

## Criar um projeto no Azure AI Studio. ❣️

1. Abrir o Azure AI Studio (https://ai.azure.com)
2. Criar um hub de IA no aure para hospedagem de projetos:
	+ nome do hub:			gfaule_ai-3621
	+ subscrição:			azure subscription1
	+ grupo de recursos:	rg-gfauleai
	+ localização:			east US
	+ conectar os serviços de IA do Azure ou o Azure OpenAI
	+ conectar o Azure AI Search
>Obs.: O hub é o recurso de nível superior do Azure para o estúdio de IA, fornecendo o ambiente de trabalho para as equipes colaborarem e gerenciarem seus aplicativos de IA.
3. Criar um projeto no hub que acabou de ser criado:
	+ hub atual:			gfaule_ai-3621
	+ nome do projeto:		gfaule-4398
4. Implantar e testar um modelo, via criação uma implantação:
	+ nome da implantação:	GPT-35-turbo
	+ versão do modelo:		0301 (padrão)
	+ tipo de implantação:	padrão
	+ recurso do OpenAI:	rg-gfauleai (a criada)
	+ limite da taxa de minutos (milhares: 5K
	+ filtro de conteúdo:	defaultV2 (padrão)
5. Após o modelo ser implantado, na página "visão geral da implantação", selecione "abrir no playground".
	+ na janela de bate-papo do playground insira a cosulta:
		* "O que é AI"

________________________________________________________________

> <span style="color:red"> **Esta foi a resposta:**
		




![Erro: Figura não encontrada!][IA]

[IA]: ./playgrounddechat.jpg

