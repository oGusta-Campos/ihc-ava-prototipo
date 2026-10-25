# Protótipo interativo AVA IF Goiano - Versão 2

O protótipo transforma as sete telas da Fase 4 em fluxos clicáveis para consulta de cursos/prazos, entrega e substituição de PDF, calendário e início de questionário.

Repositório público do código: https://github.com/oGusta-Campos/ihc-ava-prototipo

## Protótipo online

[Abrir o protótipo interativo](https://ihc-ava-prototipo.vercel.app/#courses)

Abra o link no navegador para realizar os testes. A sessão fictícia de estudante já está disponível e não exige matrícula ou senha do AVA.

## Uso local

Extraia o pacote completo. Abra `index.html` no Edge, Chrome ou outro navegador moderno. Mantenha `app.js`, `styles.css` e `Roteiro_Fase5.pdf` na mesma pasta do HTML. Não é necessária uma conta do AVA ou conexão com o Moodle.

Se baixar pelo GitHub, use **Code > Download ZIP**, extraia e abra `index.html` na raiz da pasta do repositório. Não há instalação de dependências nem compilação.

Se o navegador restringir o uso de arquivos locais, o grupo pode servir essa pasta por um servidor HTTP local e abrir a URL fornecida por ele.

## Preparação

1. Abra **Preparação de testes**, no rodapé.
2. Baixe os PDFs original e corrigido para a pasta Downloads.
3. Selecione **Inicial** e clique **Preparar cenário**.
4. Abra a tela do participante e aplique as seis tarefas do roteiro.
5. Registre sucesso, tempo e comentários. Exporte o CSV ao final.

Use **Entrega existente** para preparar T5 quando T4 não tiver sido concluída. O cenário **Falha no primeiro envio** está disponível para o piloto de recuperação; ele não integra as seis tarefas principais.

## Dados e limites

Os dados são fictícios e a data de referência é 13/10/2026. O primeiro vencimento é 14/10/2026 às 23h59. Envios e notas são simulados. O estado e os resultados de teste ficam no navegador, sem sincronização entre dispositivos. O conteúdo de um PDF enviado fica disponível na aba atual; após recarregar, a visualização pode apresentar um PDF de demonstração com o nome registrado. Não utilize credenciais ou documentos reais.

Não foram coletados resultados de estudantes. O registro começa vazio.

## Fase 6 - Versão 2 e relatório de simulação

O protótipo foi atualizado para a V2 com três ajustes: tarefas sem prazo aparecem no topo da agenda e ganham um atalho em “Meus cursos”; esse atalho limpa filtros anteriores; o rótulo “Período” permanece visível em telas pequenas; a ação de troca de arquivo usa o texto “Substituir arquivo”.

- Relatório: [Relatório da Fase 6 (dados simulados)](Relatorio_Fase6_Testes_Simulados.pdf)
- Planilha: [Dados simulados por perfil e tarefa](Fase6_Dados_Simulados.csv)
- Protótipo: [abrir a V2 no Vercel](https://ihc-ava-prototipo.vercel.app/#courses)

**Atenção:** os cinco perfis, métricas, tempos e comentários do relatório/CSV são inteiramente fictícios, conforme simulação solicitada. Não houve sessões com alunos. Não apresente esses valores como coleta empírica; substitua-os por resultados reais caso o docente exija testes com participantes.
