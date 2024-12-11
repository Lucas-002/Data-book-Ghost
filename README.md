

#  Data-book Ghost  

---

##  Descrição  

O programa Data-book Ghost foi desenvolvido para resolver um problema real em meu antigo trabalho. Ele foi usado para organizar automaticamente um grande número de arquivos em um data-book, economizando tempo e reduzindo erros humanos no processo manual de organização.

Devido à sua funcionalidade prática e à ideia de se "esconder" os processos de organização de arquivos em segundo plano, foi apelidado de Data-book Ghost.

O programa cria estruturas de diretório automaticamente com base no nome dos arquivos, facilitando sua categorização de maneira eficiente.

---

##  Funcionalidades  

- **Organiza arquivos automaticamente** em pastas hierárquicas com base nos nomes dos arquivos.  
- Cria pastas no formato padrão, com base em padrões extraídos do nome do arquivo.  
- Remove caracteres inválidos para evitar falhas de diretório.  
- Divide os arquivos com base em estruturas inteligentes, facilitando sua categorização.  
- Detecta padrões específicos no nome do arquivo para realizar verificações avançadas.

---

##  Pré-requisitos  

Antes de executar o código, verifique que você tem o seguinte:

- **Python 3.x** instalado no seu sistema.  
- Biblioteca `tkinter` configurada (já inclusa por padrão na maioria das distribuições Python).

---

##  Como usar?

1. Clone o repositório no seu computador ou faça o download diretamente:  
   ```bash
   git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   ```
2. Instale as dependências caso seja necessário.  
3. Execute o código no seu ambiente Python:  
   ```bash
   python script.py
   ```
4. Uma janela abrirá solicitando a pasta de origem com os arquivos que deseja organizar. Selecione-a.  
5. O programa criará automaticamente as pastas e moverá os arquivos para seus respectivos diretórios.

---

##  Estrutura de diretórios gerada pelo exemplo  

Ao utilizar os nomes de exemplo abaixo, vejamos a estrutura esperada no diretório de destino:

Os nomes de exemplo usados:  
```
- 1505-025 MC ELE  
- 1505-028 PRE-COM ELE  
- 1505-028 PRE-COM INS  
- 1509-025 MC ELE  
```

---

##  Exemplos de Execução  

Após selecionar a pasta onde estão os arquivos, os nomes dos arquivos:  

```
- 1505-025 MC ELE  
- 1505-028 PRE-COM ELE  
- 1505-028 PRE-COM INS  
- 1509-025 MC ELE  
```

Serão automaticamente organizados em uma estrutura de diretório semelhante ao exemplo acima.

---

##  Observações  

- Certifique-se de selecionar a pasta com os arquivos desejados no início do programa.  
- O script organiza os arquivos em diretórios aninhados, portanto, verifique se o ambiente está configurado corretamente antes de rodar.

---

##  Contribuições  

Caso deseje sugerir melhorias, corrigir bugs ou adicionar funcionalidades, sinta-se à vontade para abrir um **Issue** ou um **Pull Request** no repositório.

---
