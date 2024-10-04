# Fundamentos de segurança da informação

## O que é segurança da informação?

Segundo NIST, é a proteção de informações e sistemas de informação contra o acesso, o uso, a divulgação, a interrupção, a modificação ou a destruição não autorizados, a fim de fornacer confidencialidade, integridade e disponibilidade.

## Três pilares de SI

-  **Confidencialidade:** Tem o objetivo de controlar o acesso por múltiplos fatores, autenticação e criptografia.
	1. Especificar requisitos mínimos para uma senha de segurança;
	2. Autenticação multifator;
	3. verificação de senha fraca;
	4. Identificador e gerenciador de sessões.

-  **Integridade:** Manter as características originais dos dados, conforme sua criação.
	1. Validação de dados, como hashes.
	2. Verificação de duplicidade;
	3. Tratamento de dados de entrada, como caracteres especiais e comandos.

-  **Disponibilidade:** Quando for preciso, deixar os dados disponíveis para o que for necessário.
	1. Recursos de redundância, como backup de dados e balanceamento de carga;
	2. Infraestrutura em nuvem;
	3. Gestão de vulnerabilidade.

## Principais diretrizes

### Política de segurança da Informação (PSI)

- Boas práticas para proteção das informações.

### Política de Classificação da Informação

- Conhecer o tipo de informação, a sua criticidade e o público rara definir o controle mais adequado. 

## Classificação da Informação

Toda e qualquer informação, seja ela física ou lógica, deve ser classificada de acordo com sua sensibilidade, criticidade e valor. 

A classificação deve tratar as informações durante o seu ciclio de vida, ou seja, sua criação, edição, compartilhamento, armazenamento e descarte.

Classificar a informação facilita a aplicação da devida proteção das informações e reduz a probabilidade de ocorrer acidentes.

### Níveis de Classificação

- **Confidencial:** Informações altamente sigilosas e que não podem ser divulgadas para evitar danos à empresa, terceiros, funcionários e clientes.

    Requer medidas de controle e proteção rigorosas contra acessos, cópias, reproduções ou divulgações não autorizados.

    Destinatário consegue apenas consultar o documento.

    ⚠️ **Sob essa classificação, o vazamento de dados podem causar impactos significatovos a empresa.**


- **Restrita:** Informações exclusivas de alguns profissionais e/ou determinadas áreas. Significa que nem todos têm acesso à elas. Os dados são disponibilidados apenas aos destinatários nos quais vocẽ delega confiança para tratar do assunto.
        Exemplos:
        - E-mail com feedback;
        - Divulgação de metas e resultados institucionais;
        - Informações sobre produtos, serviços e projetos;
        - Dados ou informações referentes às políticas comerciais.

    ⚠️ **Sob essa classificação, o vazamento de dados podem causar impactos significatovos a empresa.**


- **Interna:** Informações que competem aos profissionais, estagiários, prestadores de serviços da empresa e precisam de cuidados para evitar a divulgação ao público externo.
        Exemplos:
        - Comunicados;
        - Políticas e normas corporativas;
        - Procedimentos operacionais e técnicos;
        - Relações de endereços de e-mail internos;
        - informações disponibilizadas no Intranet.


- **Pública:** Informações que podem ser divulgadas sem restrições para o público em geral, incluindo clientes, fornecedores, impresa, concorrentes, entre outros.

    Não oferecem risco algum à empresa, seus colaboradores e clientes se divulgada.

## Engenharia Social

É a habilidade de conseguir acesso a informações ou áreas importantes de algo ou alguém através de habilidades de persuasão.

Os investimentos para proteção das informações estão cada vez maiores e as tecnologias mais avançadas, com isso os fraudadores atacam o fator humano, a parte do processo de controle de segurança que tem menos atenção das empressas.

### Táticas de abordagem:

- **Baiting:** utilização de iscas físicas ou digitais com malware;
- **Phishing:** sms, ligações de voz ou email para obter credenciais ou instalar malware;
- **Dumpster Diving:** Descarte não cuidadoso de informações de todos os níveis de classificação.

### Dicas de Prevenção

1. Observe com cuidado todas as informações;
2. não baixe arquivos e anexos em e-mails suspeitos;
3. Valide os links e o remetente dos e-mails;
4. Descarte corretamente os documentos e equipamentos;
5. Pratique o "mesa e tela limpa" ao mesmo o bloquear a tela e deixar o necessário em seu ambiente de trabalho.

## Boas práticas e diretrizes

### Compartilhamento de acesso

As credenciais de acesso, de qualquer sistema, constituem a identificação do usuário, isto é, só ele é autorizado a acessar e trabalhar aquelas informações.

*Não compartilhe suas credenciais de acesso!*

### Armazenamento

As informações devem ser armazenadas nos repositórios oficiais, onde estarão seguras com os devidos controles de proteção.
 - Udemy;
 - OneDrive;
 - Sharepoint.

### Softwares e malwares

Softwares maliciosos e malwares são muito comuns em programas ou arquivos baixados da internet, portanto, é necessário ter muita cautela!

Avalie sempre a lista de softwares homologados antes de intalar algo em seu equipamento.

### Senha segura

 - Evite usar nomes, sobrenomes, apelidos, datas de aniversário, n° de celular, placa de carro;
 - Crie senhas diferentes para cada conta, sistema ou site que precisar;
 - Troque suas senhas com frequência;
 - Use um aplicativo de *cofre de senhas*;
 - Semque que disponível, utilize um segundo fator de autenticação(MFA);
 - Reporte ao time InfoSec situações suspeitas que pedem suas informações;
 - Sempre que possível use letras maiúsculas e minúsculas, números e caracteres especiais.

### Uso da internet

O conteúdo acessado na internet e o uso do e-mail corporativo deve respeitar todas as diretrizes e normas de segurança e privacidade, publicadas e divulgadas em nossas políticas.

**Evite o uso de ferramentas de comunicação instantâneas para tratar assuntos sensíveis e compartilhar arquivos!**

Para compartilhar arquivos, reveja o tópico: <a href="#armazenamento">armazenamento</a>

### Multi-factor Authenticator (MFA)

É um controle que demanda dois ou mais elementos de autenticação para identificar um usuarío.

#### Tipos de autentificação mais utilizados:

- O que sei: exigido algo conhecido. Ex.: login, resposta a uma pergunta secreta.
- O que tenho: necessário algo físico. Ex.: token, cartão inteligẽnte ou app authenticator.
- Quem sou: utilizado características físicas do ser humano como a impressão digital, reconhecimento de voz ou face.

O tipo *Quem sou* talvez seja um dos controles mais populares.

### MS Authenticator

O aplicativo Microsoft authenticator é utilizado para gerar um token de verificação para acessar a plataforma Office365.

a cada 14 dias, é solicitado um novo código para acessar os aplicativos que possuem o MFA.

*ao trocar de dispositivo, antes de desativar o MFA no dispositivo antigo, é necessário utilizá-lo para realizar o cadastro do mesmo no novo dispositivo móvel.*

### Atualização de software

Além das correções e proteções contra novas vulnerabilidades identificadas pelos vendors, ter seu softwares e SO atualizados gera ganhos em desempenho, compatibilidade, estabilidade, evita interrupções e aproveita de novos recursos e funcionalidades.

### Incidentes de segurança

É um evento de segunrança, ou um conjunto deles, que podem impactar a disponibilidade, integridade e confidencialidade de um ativo de informação, assim como qualquer violação da Política de Segurança da Informação.

#### Tipos de incidentes:

- Ferramentas não autorizadas instaladas;
- Vírus e códigos maliciosos;
- Tentativas não autorizadas de acesso;
- Compartilhamento de credenciais.



### Redes Wi-Fi

#### Em redes públicas

- Evite conectar-se a redes abertas;
- Utilize uma VPN confiável;
- Desative a opção de conexão automática nas redes WI-Fi;
- Desabilite o compartilhamento de arquivos e impressoras;
- Não instales APPs que quebram senhas ou as descobrem para conectar a redes Wi-Fi protegidas.

#### Em sua rede doméstica

- configure uma senha forte para seu roteador, troque-a periodicamente. utilize os padrões WPA2 ou WPA3;
- Mantenha o firmware atualizado;
- Mude os padrões de fábrica com o nome de sua rede (SSID) e credenciais de administrador do roteador;
- Desabilite o acesso remoto ao roteador para manutenções;
- Fique atento aos sites onde vai inserir informações confidenciais.

## Segurança em IA Generativa

### O que é IA Generativa?

Inteligência Artificial Generativa é um sub campo da IA que se concentra na criação de novos conteúdos, dados ou informações como texto, imagem, vídeos, música ou código, a partir de um conjunto de entradas existentes.

O algoritmo de IA aprendem com os dados fornecidos e são capazes de gerar saídas semelhantes, mas não idênticas, com base no conhecimento adquirido durante o treinamento.

### Ambiente e utilização de ferramenta IA

Há diversas ferramentas gratuitas e pagas, antes de usa-las, leia atentamente o termo de uso ou o contrato.

  *Saber como os dados inseridos serão usados é imprescindível para a segurança dessas informações. Vocẽ poderá involuntariamente autorizar o uso ou deixar os dados disponíveis para terceiros.*

### Como proteger os dados e informações

- Remova dados pessoais, senhas ou tokens das consultas que enviar, independente que sejam dados de ambientes, desemvolvimento ou produção.
- Quando possível utilize mascaramento de dados.
- Troque nas consultas qualquer dado real de clientes ou da empresa, como nomes próprios das empresas, comentários de código ou casos reais.

### Controle mínimos de segurança

- Homologação para validar os controles técnicos;
- Análise de riscos;
- Utilizar o Jira para solicitações de acessos às ferramentas de IA;
- Documentar no Share point ou Confluence os manuais e processos para utilização das ferramentas de IA;
- Realizar os treinamentos obrigatórios e participar das ações de capacitação e concientização sobre o tema.
