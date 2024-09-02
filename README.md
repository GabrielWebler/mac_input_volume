# Portugês Brasil
# Ajuste de volume automático do microfone no MacOS

As aplicações Zoom e Meet tem o auto ajuste de volume do microfone para ajustar melhor o redução ruido e também não gerar um audio muito alto nas reuniões.
Incluindo essa entrada no ```crontab``` o OS irá ajustar o volume para 50 sempre que estiver abaixo.

Para incluir, siga os passos abaixo:

1. Copiar a linha inteira
2. Abrir o terminal
3. Executar ```crontab -e```
4. Se estiver usando o **VIM**
   1. Se já houver algo configurado no crontab, com as setas, navege com o cursor até a última linha e aperte a tecla **O** para inserir uma linha abaixo e iniciando a inserção de texto (no rodapé aparecerá **'--- INSERT ---'**). Se não houver nenhuma linha, basta apertar a tecla **I** para iniciar a inserção de texto (no rodapé aparecerá **'--- INSERT ---'**)
   3. Cole a linha que foi copiada
   4. Aperte e telca **Esc** uma vez (o **'--- INSERT ---'** sumirá)
   5. Digite o comando ```:x``` (o x tem que ser em minúsculo) que salvará e fechará o **VIM**
5. Se estiver usando o **Nano**
   1. Se já houver algo configurado no crontab, com as setas, navege com o cursor até a última linha e aperte a tecla **Enter** para inserir uma linha abaixo. Se não houver nenhuma linha, é só seguir para o próximo passo
   2. Cole a linha que foi copiada
   3. Execute **Ctrl** + **x** para salvar as alterações
   4. Confirme a sobreposição do arquivo e confirme o salvamento
6. Com isso voltará para o terminal e pode fecha-lo


# English
# Automatic microphone volume adjustment in macOS
Zoom and Meet applications have automatic microphone volume adjustment to better adjust noise reduction and also not generate a very loud audio in meetings.
By including this entry in crontab, the OS will adjust the volume to 50 whenever it is below.

To include it, follow the steps below:

1. Copy the entire line
1. Open the terminal
1. Run ```crontab -e```
1. If you are using **VIM**
   1. If there is already something configured in the crontab, use the arrows to navigate the cursor to the last line and press the **O** key to insert a line below and start inserting text (at the footer will appear **'--- INSERT ---'**). If there is no line, just press the **I** key to start inserting text (at the footer will appear **'--- INSERT ---'**)
   2. Paste the copied line
   3. Press the **Esc** key once (the **'--- INSERT ---'** will disappear)
   4. Type the command **:x** (the x must be in lower case) which will save and close the **VIM**
2. If you are using **Nano**
   1. If there is already something configured in the crontab, use the arrows to navigate the cursor to the last line and press the **Enter** key to insert a line below. If there is no line, just go to the next step
   2. Paste the copied line
   3. Execute **Ctrl** + **x** to save the changes
   4. Confirm the file overwrite and confirm the save
3.  With that you will return to the terminal and can close it
