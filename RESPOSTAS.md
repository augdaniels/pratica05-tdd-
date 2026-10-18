1. No Ciclo 1 usamos return 70. Por que isso é aceitável no TDD? O que
obrigou a escrever a soma de verdade?
Porque no começo do TDD a intenção é fazer o teste passar com a implementação mínima possível, mesmo que provisória. Depois, novos testes exigem uma solução real.

2. No Ciclo 3, por que testar com 69 e 70, e não com 50 e 90?
Porque 69 e 70 estão ao redor do limite de aprovação. Eles verificam se o operador >= foi implementado corretamente.

3. No Ciclo 4, o que mudou na refatoração? Como você teve certeza de
que não quebrou nada?
A validação repetida em "ifs" foi convertida em um metodo validarNota(). Os testes confirmam que o comportamento permaneceu igual.

4. No Ciclo 8, por que alteramos os testes antes de mudar o código?
Porque os testes documentam o novo requisito e mostram que a implementação antiga não atende mais ao comportamento esperado.

5. Qual ciclo foi o mais difícil para você, e por quê?
Ciclo 7 pois houve uma maior exigencia nas implementações e requisitos para aprovação, havendo certa confusão na iplementação no codigo. 