# brutephone
wordlist para brute force baseada em números telefônicos brasileiros

ex: < 81******
          94******
              87******
                 99******
/>

use:
$ crunch 8 8 -t 99%%%%%% > wordlist.txt    # -t indica que o 99 permanecerá, e apenas os % serão gerados novos números
$ crunch 8 8 -t 98%%%%%% >> wordlist.txt   # o >> adiciona a nova lista ao arquivo ao invés de sobrescrever
