# SiteDoisBlazor

Atividade de Desenvolvimento Web — Usabilidade, Dev. Web, Mobile e Jogos.
Professor: Daniel Henrique Matos de Paiva.

## Equipe (até 5 alunos)
Victor Rodrigues da Silva
Nicolas Ribeiro Rocha

## Requisitos

- SDK do .NET 8.
- Opcional: Visual Studio 2022 com a carga de trabalho ASP.NET e desenvolvimento Web.

## Executar

Abra o terminal na pasta que contém `SiteDoisBlazor.csproj`:

```bash
dotnet restore
dotnet build
dotnet watch
```

Acesse o endereço exibido no terminal. No Visual Studio, abra `SiteDoisBlazor.sln` e pressione F5.

## Exercícios

| Arquivo | Rota | Funcionalidade |
| --- | --- | --- |
| Components/Pages/Conversor.razor | /conversor | F = (C × 9/5) + 32 |
| Components/Pages/Media.razor | /media | Média de duas notas; aprovado a partir de 7 |
| Components/Pages/Sorteio.razor | /sorteio | Número aleatório entre 1 e 100 |
| Components/Layout/NavMenu.razor | — | Navegação por NavLink |

Os três componentes interativos possuem `@rendermode InteractiveServer` na segunda linha.

## Conferência manual antes da entrega

1. Navegue pelas três páginas usando o menu, sem digitar suas URLs.
2. Conversor: 0 °C → 32 °F; 100 °C → 212 °F; -40 °C → -40 °F.
3. Média: ao abrir, nenhum resultado é mostrado; 6 e 8 → 7, Aprovado! em verde; 5 e 6 → 5,5, Reprovado! em vermelho.
4. Sorteador: ao abrir, nenhum número é mostrado; cada clique apresenta um inteiro de 1 a 100. Repetições são possíveis.

## Publicar no GitHub

Crie um repositório chamado `site-dois-blazor` na sua conta. Na criação, selecione README, `.gitignore` **VisualStudio** e licença **MIT**, conforme o enunciado.

Clone o repositório criado:

```bash
git clone https://github.com/SEU_USUARIO/site-dois-blazor.git
cd site-dois-blazor
```

Copie para essa pasta os arquivos deste projeto (incluindo os arquivos ocultos). Pode manter o `.gitignore` completo do Visual Studio gerado pelo GitHub e a licença MIT criada lá. Substitua o README pelo deste projeto e preencha a equipe.

```bash
git add .
git commit -m "Implementa exercícios de Blazor nível 2"
git push origin main
```

Entregue o link do repositório ao professor.

## Validação desta entrega

Código revisado estruturalmente. Não compilado nem executado no ambiente de geração, pois ele não possui o SDK .NET. Execute a compilação e a conferência manual acima antes de entregar.

## Licença

MIT. Veja `LICENSE`.
