# Front-end Challenge - Rastreador de Endereços IP

## Sobre o Teste

Seu desafio é construir este aplicativo Rastreador de Endereços de IPs e fazê-lo parecer o mais próximo possível do design possível. Para obter os locais do endereço IP, você usará a [API de geolocalização por IP da IPify](https://geo.ipify.org/). Para gerar o mapa, recomendamos o uso do [LeafletJS](https://leafletjs.com/).

### Requisitos básicos

- Você deve usar React;
- Você deve usar TypeScript;
- Você deve usar Styled-Components;
- Você deve aplicar o conceito de componentes em sua aplicação;
- Você deve criar um repositório e compartilhar com a gente;
- Quero conseguir rodar seu projeto rodando yarn/npm start, ou seja, seu `README.md` deve conter os comandos e qualquer informação útil pra rodar sua aplicação;

### Os usuários devem ser capazes de:

- Visualizar o layout ideal para cada página, dependendo do tamanho da tela do dispositivo;
- Veja os estados de foco para todos os elementos interativos na página;
- Veja seu próprio endereço IP no mapa no carregamento inicial da página;
- Pesquise quaisquer endereços IP ou domínios e veja as principais informações e localização;

### Requisitos adicionais

- Precisamos ter certeza que nossa aplicação funciona conforme o esperado, alguns testes seriam bem vindos, estamos usando por aqui enzyme e jest, mas sinta-se a vontade para testar com o que sente maior conforto;
- Pense que sua aplicação passará por 3 ambientes, DSV - HML - PRD, monte build e use variaveis de ambiente;
- Sei que não faz sentido para uma aplicação pequena mas seria legal para mostrar seus conhecimentos usar Context API para gereciamento de estados;
- Hospedar seu projeto gratuitamente em um desses host:
  -> [GitHub Pages](https://pages.github.com/);
  -> [Vercel](https://vercel.com/);
  -> [Netlify](https://www.netlify.com/);

### Método de avaliação

- Boas práticas e patterns;
- Código e estrutura da aplicação;
- Componentização e fluxo do dado;
- Facilidade de leitura de código (código limpo e fácil é sempre bom; :D

---

## Onde encontrar tudo

- Sua tarefa é construir o projeto para os designs dentro da pasta `/design`. Você encontrará uma versão móvel e uma versão desktop do design;
- Os designs estão no formato estático JPG. Usar JPGs significa que você precisará usar seu bom senso para estilos como `font-size`, `padding` and `margin`;
- Você encontrará todos os recursos necessários na pasta `/images`. Os `assets` já estão otimizados;
- Também existe um arquivo `style-guide.md` contendo as informações de que você precisa, como paleta de cores e fontes;

---

⚠️ **IMPORTANTE** ⚠️ : Para usar a API de geolocalização por IP da IPify, você precisa se inscrever para uma conta gratuita. Você não precisará adicionar detalhes de cartões para fazer isso e é um processo muito rápido. Isso irá gerar uma chave API para você. Normalmente, você seria capaz de restringir sua chave de API a um URL específico (seu próprio domínio). Isso garante que outras pessoas não possam usar sua chave de API em seus próprios sites. O IPify não tem esse recurso, mas como você não está adicionando os detalhes do seu cartão, isso não é um problema. **Portanto, certifique-se de se inscrever apenas para a conta gratuita e NÃO insira os detalhes do cartão**.

Para a API de mapeamento, recomendamos o uso do [LeafletJS](https://leafletjs.com/). O uso é gratuito e não requer uma chave de API. Se você decidir usar outra API, como Google Maps ou Mapbox, certifique-se de proteger sua chave de API. Aqui estão os guias para o Google Maps e o Mapbox, certifique-se de lê-los completamente:

- [Práticas recomendadas de chave de API do Google Developers](https://developers.google.com/maps/api-key-best-practices)
- [Como usar o Mapbox com segurança](https://docs.mapbox.com/help/troubleshooting/how-to-use-mapbox-securely/)

Expor sua chave de API publicamente pode fazer com que outras pessoas a usem para fazer solicitações para seus próprios aplicativos, se as precauções adequadas não estiverem em vigor.

---

** Boa sorte e faça o teste da forma que você se sentir confortável**. 🚀
