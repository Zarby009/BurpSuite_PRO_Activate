![BurpSuite-Pro-Latest](https://github.com/TariqullslamHridoy/BurpSuite-Pro-Latest/assets/110732307/5489fb56-4054-44ee-93b9-f44a9b4fd283)

# Instalação do BurpSuite Pro

Bem-vindo à sua jornada de instalação do BurpSuite Pro! Siga os passos abaixo para configurar tudo corretamente:

## Passo a Passo

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/Zarby009/BurpSuite_PRO_Activate.git
    ```

2. **Baixe o Executável**:
    - Visite o site oficial do BurpSuite e **baixe o arquivo .jar** da versão Pro. Este arquivo contém a instalação completa.
    - E eles mesmos disponibilizam :)
3. **Acesse a pasta do projeto**:
    ```bash
    cd BurpSuite-Pro-Latest
    ```
4. **Execute o Script de Instalação (Irá baixar automaticamente o BurpPro.java)**:
    ```bash
    sudo sh install.sh
    ```
    O que ele faz? baixa automaticamente o Burp Pro com .jar e coloca dentro do executável Burp esse código para facilitar a inicializacao:
   ```bash
    java --add-opens=java.desktop/javax.swing=ALL-UNNAMED--add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -javaagent:$(pwd)/loader.jar -noverify -jar $(pwd)/burpsuite_pro_v$version.jar &
   ```
5. **Se quiser, pode inicializar com:**
   com o arquivo do BurpSuite.jar na mesma pasta do projeto:
   ```bash
   java -jar loader.jar com o arquivo do BurpSuite.jar na mesma pasta do projeto
    ```
    ou
digitar apenas Burp (apenas se tiver rodado o install.sh)
   ```bash
   Burp

    ```


   
---
# Se der erro: 
   - verifique o nome do burppro, renomeie ele para mais ou menos assim: burpsuite_pro_v2024-1-1.jar

se der erro, verifique o nome do burppro, renomeie ele para mais ou menos assim: burpsuite_pro_v2024-1-1.jar
---

# Como Rodar

Após a instalação, é hora de colocar o BurpSuite Pro em ação! Você pode iniciar o programa de duas maneiras:

```bash
Burp
```

ou

```bash
java -jar loader.jar
```
**Personalize sua Licença**
## Instruções de Ativação

Para ativar o BurpSuite Pro, siga os passos abaixo com atenção:

1. **Insira seu Nome/Nick**: 
   - Após iniciar o BurpSuite Pro, você terá a opção de alterar seu nome ou nickname. Isso é importante, pois essa alteração irá modificar a licença que será gerada. Certifique-se de escolher um nome que você gostaria de usar para sua licença.

2. **Copie a Licença**: 
   - Clique no botão **'Run'** para iniciar o processo. **Nota**: Durante essa etapa, é comum que apareça um erro relacionado ao Java Runtime Environment (JRE). **Não se preocupe!** Esse erro é normal e você deve apenas aguardar alguns segundos enquanto o programa é carregado.

3. **Aceite os Termos**: 
   - Depois que o programa carregar, você será solicitado a aceitar os termos de uso. Leia atentamente e, se concordar, cole a licença que você obteve anteriormente na caixa de texto correspondente. Em seguida, pressione o botão **'Next'** para continuar.

4. **Ativação Manual**: 
   - Na próxima tela, você verá a opção para **Ativação Manual**. Selecione essa opção para prosseguir com o processo de ativação.

5. **Solicitação de Licença**: 
   - Uma vez que você selecionar a ativação manual, um valor de **"Activation Request"** será gerado. Copie esse valor com cuidado, pois você precisará colá-lo na janela do Java do nosso Bypass. Na janela do Bypass, localize o campo à direita onde está escrito **'Activation Request'** e cole o valor que você copiou.

6. **Resposta da Licença**: 
   - Após colar a solicitação, você receberá uma **"Activation Response"**. Copie esse valor e volte para o BurpSuite Pro. Na interface do BurpSuite, procure a caixa que diz **'Paste Response'** e cole a resposta que você copiou. Depois de colar, clique em **'Next'** e finalize o processo pressionando **'Done'**.

Agora você deve estar pronto para utilizar o BurpSuite Pro com a licença ativada!



**Observações Importantes**
* Modifique a String da Licença: Altere a string de licença do carregador para "license to XXXXXXX", por exemplo, "license to xiv3r".
* Copie a Chave de Licença: Pegue a chave do carregador e cole no BurpSuite, em seguida, clique em Próximo.
* Ativação Manual: Selecione a opção de Ativação Manual.
* Solicitação de Licença: Copie a solicitação de licença do BurpSuite Pro e cole no Keygenerator.
* Resposta da Licença: Por fim, copie a resposta da licença do Keygenerator e cole no Burp Suite Pro. Clique em Próximo e depois em Concluir.








