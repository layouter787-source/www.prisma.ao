# PRISMA — Website institucional

Website demonstrativo em português de Angola, feito com HTML, CSS e JavaScript sem dependências de build.

## Executar localmente
Abra `index.html` no navegador ou sirva a pasta com qualquer servidor estático.

## Deploy na Vercel
1. Importe `layouter787-source/www.prisma.ao` em https://vercel.com/new
2. Framework Preset: **Other**.
3. Build Command e Output Directory: vazios.
4. Faça Deploy.

## Design
- Página simplificada, com navegação curta e menos texto.
- Garrafa PRISMA ilustrada em CSS, com tampa azul, corpo transparente e rótulo da marca.
- Superfícies transparentes sem blur ou gradientes aplicados ao efeito de vidro.
- Animação ilustrativa da linha de engarrafamento.
- Layout adaptável a telemóveis e preferência por movimento reduzido.

## Referências de design
- Apple Liquid Glass: https://developer.apple.com/documentation/technologyoverviews/liquid-glass
- Apple Human Interface Guidelines — Materials: https://developer.apple.com/design/human-interface-guidelines/materials
- Expo GlassEffect: https://docs.expo.dev/versions/latest/sdk/glass-effect/

Nota técnica: `expo-glass-effect` é uma biblioteca nativa Expo/React Native, não uma dependência de um site HTML/CSS. O site usa CSS próprio para desenhar superfícies transparentes, sem simular blur.

## Nota importante
PRISMA é uma marca fictícia para fins demonstrativos. O contacto `geral@prisma.ao` e a localização são dados de exemplo. A garrafa apresentada é uma ilustração CSS baseada na referência visual enviada, não uma fotografia nem um ficheiro de embalagem industrial aprovado. Substitua os dados e valide rótulo, produto e informações legais antes de uso comercial.
