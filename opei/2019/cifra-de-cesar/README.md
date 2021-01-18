<p align="center">
  <img width="250px" src="../../../docs/imagens/opei/logo_opei.png"/> 
</p>

 <h1 align="center" style="font-weight: bold">OPEI 2019 - <span style="font-style: italic">Cifra de Cesar</span></h1>

Camila é uma menina de 13 anos bastante curiosa e que adora passar o tempo mexendo em suas redes sociais. Ultimamente, tem se falado bastante sobre privacidade dos dados e como o whatsapp(WPP) é criptografado ponta a ponta a fim de evitar que as mensagem sejam lidas por pessoas diferentes sem ser as que participam da conversa. Camila achou interessante essa funcionalidade do WPP e quis saber mais como funcionava a criptografia. Por isso, começou a estudar sobre e achou informações sobre a Cifra de Cesar, um dos métodos mais simples de criptografia.

A cifra de César, também conhecida como cifra da troca, é um tipo de cifra de substituição, onde todas as letras do alfabeto são substituídas por outras deslocando o alfabeto em um número fixo de vezes. =

Sabendo disso, Camila a partir de agora só quer conversar com seus amigos utilizando a Cifra de César para que outras pessoas que leiam a conversa, não saibam seu conteúdo. Contudo, seus amigos não sabem como funciona e seu objetivo é ajudar o grupo de Camila a se comunicar com ela. Crie um programa que receba as informações criptografadas por Camila e decodifique-as.

## Entrada ⬅️ 
A primeira linha da entrada consiste em um inteiro N que corresponde ao valor do deslocamento do alfabeto.
A segunda linha da entrada consiste em uma string M que corresponde a mensagem de Camila criptografada.

## Saída ➡️
A saída corresponde a uma única string que representa a mensagem decodificada com uma quebra de linha no final.

---
## Exemplo:
*Entrada*:
```
3
rolpsldgd#shuqdpexfdqd#gh#lqirupdwlfd
```
*Saída*:
```
olimpiada pernambucana de informatica
```

<br/>

## Soluções adicionadas:
| Ícone | Linguagem | Tag | Nome |
|:---:|:---:|:---:|:---:|
| <svg viewBox="0 0 128 128" style="width: 80px;"><linearGradient id="a" gradientUnits="userSpaceOnUse" x1="70.252" y1="1237.476" x2="170.659" y2="1151.089" gradientTransform="matrix(.563 0 0 -.568 -29.215 707.817)"><stop offset="0" stop-color="#5A9FD4"></stop><stop offset="1" stop-color="#306998"></stop></linearGradient><path fill="url(#a)" d="M63.391 1.988c-4.222.02-8.252.379-11.8 1.007-10.45 1.846-12.346 5.71-12.346 12.837v9.411h24.693v3.137h-33.961c-7.176 0-13.46 4.313-15.426 12.521-2.268 9.405-2.368 15.275 0 25.096 1.755 7.311 5.947 12.519 13.124 12.519h8.491v-11.282c0-8.151 7.051-15.34 15.426-15.34h24.665c6.866 0 12.346-5.654 12.346-12.548v-23.513c0-6.693-5.646-11.72-12.346-12.837-4.244-.706-8.645-1.027-12.866-1.008zm-13.354 7.569c2.55 0 4.634 2.117 4.634 4.721 0 2.593-2.083 4.69-4.634 4.69-2.56 0-4.633-2.097-4.633-4.69-.001-2.604 2.073-4.721 4.633-4.721z"></path><linearGradient id="b" gradientUnits="userSpaceOnUse" x1="209.474" y1="1098.811" x2="173.62" y2="1149.537" gradientTransform="matrix(.563 0 0 -.568 -29.215 707.817)"><stop offset="0" stop-color="#FFD43B"></stop><stop offset="1" stop-color="#FFE873"></stop></linearGradient><path fill="url(#b)" d="M91.682 28.38v10.966c0 8.5-7.208 15.655-15.426 15.655h-24.665c-6.756 0-12.346 5.783-12.346 12.549v23.515c0 6.691 5.818 10.628 12.346 12.547 7.816 2.297 15.312 2.713 24.665 0 6.216-1.801 12.346-5.423 12.346-12.547v-9.412h-24.664v-3.138h37.012c7.176 0 9.852-5.005 12.348-12.519 2.578-7.735 2.467-15.174 0-25.096-1.774-7.145-5.161-12.521-12.348-12.521h-9.268zm-13.873 59.547c2.561 0 4.634 2.097 4.634 4.692 0 2.602-2.074 4.719-4.634 4.719-2.55 0-4.633-2.117-4.633-4.719 0-2.595 2.083-4.692 4.633-4.692z"></path><radialGradient id="c" cx="1825.678" cy="444.45" r="26.743" gradientTransform="matrix(0 -.24 -1.055 0 532.979 557.576)" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#B8B8B8" stop-opacity=".498"></stop><stop offset="1" stop-color="#7F7F7F" stop-opacity="0"></stop></radialGradient><path opacity=".444" fill="url(#c)" enable-background="new" d="M97.309 119.597c0 3.543-14.816 6.416-33.091 6.416-18.276 0-33.092-2.873-33.092-6.416 0-3.544 14.815-6.417 33.092-6.417 18.275 0 33.091 2.872 33.091 6.417z"></path></svg> | Python | @fabiopapais | Fábio Papais |