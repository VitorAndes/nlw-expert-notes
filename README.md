# Site de anotações
![image](https://github.com/user-attachments/assets/d4808873-aac1-4f37-85fb-c2d07ed319a0)



## Descrição

Este projeto foi desenvolvido em durante uma NLW fornecida pela Rocketseat. Um app para criar e gerenciar notas de forma prática e intuitiva. As notas são salvas localmente no dispositivo do usuário, garantindo privacidade e acesso offline. O usuário pode criar notas utilizando tanto a voz quanto a escrita, e também pode filtrar notas para facilitar a organização e a busca.

## Funcionalidades

- **Criação de Notas**: 
  - **Via Escrita**: Permite ao usuário digitar e salvar suas notas diretamente na interface do site.
  - **Via Voz**: Utiliza reconhecimento de voz para transcrever e salvar notas.
  
- **Salvamento Local**: 
  - As notas são armazenadas localmente no navegador do usuário, utilizando o `localStorage`.
  
- **Filtro de Notas**: 
  - Sistema de filtragem de notas por palavras-chave ou datas.

## Tecnologias Utilizadas

### Libs

- **date-fns**
- **lucide-react**
- **react**
- **react-dom**
- **sonner**
- **dom-speech-recognition**

### Ferramentas de Desenvolvimento

- **tailwindcss**
- **typescript**
- **vite**

## Como Usar

1. **Acessar o Site**: Abra o site em seu navegador.
2. **Criar uma Nota**:
   - **Gravando uma Nota**: Clique em "Gravando uma nota" para ativar a função de reconhecimento de voz. Comece a falar, e o sistema transcreverá automaticamente sua voz em texto.
   - **Utilize Apenas Texto**: Clique em "Utilize apenas texto" para desativar o reconhecimento de voz e digitar sua nota manualmente.
3. **Filtrar Notas**: Utilize a barra de pesquisa ou filtros.
