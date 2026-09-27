# GalS — Secções de Betão Armado e Pré-esforçado

O GalS verifica **secções de betão armado e pré-esforçado** segundo o **Eurocódigo 2**
(NP EN 1992-1-1, com o Anexo Nacional português), no estado limite último e em serviço.
Nasceu em 1992; a versão atual é de 2026.

## O que faz

- **Secções**  poligonais fechadas quaisquer, com a armadura passiva e pré-esforçada.
- **Estado limite último**: flexão composta desviada (N, My, Mz), com o fator de
  segurança, o diagrama de interação N-M e o relatório com o plano de extensões,
  as tensões e a posição da linha neutra.
- **Estados limites de serviço**: limitação de tensões (§7.2), fendilhação e
  momento de fendilhação (§7.3), com a fluência e a retração do Anexo B.
- **Pré-esforço** por cabos aderentes: as perdas imediatas e diferidas (5.46),
  a relaxação, a transferência e a verificação ao ELU com a extensão prévia.
- **esforços lidos do Excel**, ou colados do Clipboard, com os resultados devolvidos 
  ao Excel.
- **Textos de apoio**: alguns documentos que explicam, passo a passo e com um
  exemplo, o cálculo da fluência, da retração, da relaxação e dos ELU com
  pré-esforço. 

## Instalar

1. Na página [**Releases**](https://github.com/GalsEM/GalS/releases/latest),
   descarregue o `GalS_Setup_<versão>.exe`.
2. Execute-o. A instalação é feita para o seu utilizador e **não pede permissões
   de administrador**.

Requisitos: Windows 10 ou 11, de 64 bits.

### «O Windows protegeu o seu PC»

O instalador não tem assinatura digital, e por isso o Windows pode mostrar este
aviso na primeira vez. Carregue em **Mais informações** e depois em
**Executar mesmo assim**. Para confirmar que o ficheiro é o publicado, compare o
seu SHA-256 com o que está nas notas da versão:

```
certutil -hashfile GalS_Setup_<versão>.exe SHA256
```

## Termos de utilização

- O GalS é **de utilização livre** e destina-se a **uso não comercial**.
- É fornecido **tal como está, sem qualquer garantia**. Os resultados devem ser
  verificados por quem os usa: a responsabilidade de um projeto é sempre do
  engenheiro que o assina, e o programa não substitui o seu juízo.

## Contacto

Para reportar uma «Não convergência» ou sugerir uma melhoria, use o **Contacto**
da janela *About* do programa, ou escreva para **GalS.EM.email@gmail.com**.

---

© 1992–2026 Eduardo Monteiro.
