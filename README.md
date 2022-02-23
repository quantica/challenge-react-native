# Desafio REACT NATIVE
Olá, buscando se aproximar dos problemas que encontrará no dia a dia, queremos que desenvolva um tela de listagem de estados e municípios, onde o usuário deve inicalmente ver uma lista de estados e, ao clicar em cada um, ver a lista de seus municipios.

O projeto deve ser publicado em um repositório do github e compartilhado com quem lhe enviou esse desafio.

### Requisitos funcionais
- É necessario adicionar um filtro por nome para facilitar na hora de procurar um município.
- A capital de cada estado deve estar em destaque.

### Requisitos tecnicos
- react-native
- react-navigator
- styled-components

### APIs

- Listagem de estados:
-- https://servicodados.ibge.gov.br/api/v1/localidades/estados

- Listagem de municioes por estado:
-- https://servicodados.ibge.gov.br/api/v1/localidades/estados/{UF}/distritos
