# Jogo da Forca em Python :video_game:
Este é um simples jogo da forca em Python. O jogador precisa adivinhar uma palavra oculta, digitando letras para preencher os espaços em branco. Se o jogador adivinhar corretamente todas as letras da palavra, ele vence. Caso contrário, ele perde quando suas chances acabarem.

### Como jogar :question:
Ao iniciar o jogo, uma palavra é escolhida aleatoriamente (no código atual, a palavra é definida como "carro").

O jogador precisa digitar uma letra e pressionar Enter.

Se a entrada contiver mais de uma letra, será exibida uma mensagem de erro (⚠️ ERRO, digite apenas uma letra) e o jogador poderá tentar novamente.

Se a letra já tiver sido digitada anteriormente, será exibida uma mensagem informando que a letra já foi digitada (⚠️ Você já digitou essa letra. Tente novamente) e o jogador poderá tentar novamente.

A palavra oculta é exibida com os espaços em branco preenchidos pelas letras corretas já digitadas. As letras não adivinhadas são representadas por asteriscos (*).

O jogo continua até que o jogador adivinhe corretamente a palavra ou suas chances acabem.

Se o jogador adivinhar corretamente a palavra, será exibida uma mensagem de vitória (🎉 Você venceu e escapou da forca!) e o jogo será encerrado.

Se o jogador errar uma letra, suas chances serão reduzidas em 1.

Se o jogador esgotar suas chances (chance <= 0), será exibida uma mensagem de derrota (☠️ Você perdeu! FORCA!) e o jogo será encerrado.

### Requisitos :clipboard:
Python 3.x

### Como executar o jogo :arrow_forward:

Certifique-se de ter o Python instalado em seu sistema.

Copie o código do jogo da forca para um arquivo Python (por exemplo, jogo_da_forca.py).

Abra um terminal ou prompt de comando e navegue até o diretório onde o arquivo Python está localizado.

#### Execute o seguinte comando:

python jogo_da_forca.py

### Personalização :art:
Para alterar a palavra a ser adivinhada, você pode modificar a variável palavra no código para uma palavra de sua escolha.
Divirta-se jogando a forca e boa sorte! :tada:

