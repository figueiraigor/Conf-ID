Mensagem de Commit:

feat(núcleo): Implementa fluxo de registro unificado e integração de API com CREA/gov.br

<b>Descrição do Commit:</b>

Este commit marca um marco significativo no desenvolvimento do Conf-ID, entregando a funcionalidade principal para um sistema unificado de registro profissional para engenheiros, agrônomos e geocientistas no Brasil.

<b>Principais Recursos Implementados:<B>

Fluxo de Registro Unificado: Processo de registro de usuário simplificado com um único formulário e validação automática de dados com APIs gov.br (e-Gov).

Resolve problemas relacionados a múltiplos registros regionais e elimina a entrada redundante de dados.

Melhora a precisão e eficiência dos dados por meio da validação em tempo real.

Integração Regional do CREA (API): Estabelecida uma conexão segura de API com os sistemas regionais do CREA para automatizar o envio e processamento de solicitações de registro.

Reduz erros de entrada manual de dados e simplifica a comunicação entre os sistemas Conf-ID e CREA Regional.

Permite a troca de dados perfeita para tempos de processamento mais rápidos.

Estrutura do Banco de Dados Nacional: Criado o esquema inicial do banco de dados para a plataforma central Conf-ID, projetada para armazenar e gerenciar dados de registro profissional com segurança e eficiência.

Inclui campos para RNP (Registro Nacional Profissional), detalhes do profissional, status do registro e muito mais.

Implementa medidas de segurança adequadas para proteger informações confidenciais (criptografia, controles de acesso).

<b>Próximos Passos:</b>

Desenvolver interfaces de front-end (painel do usuário, formulários de registro) para conectar com a funcionalidade de back-end implementada.

Implementar a emissão automatizada de ART (Anotação de Responsabilidade Técnica) e a integração de pagamentos com os sistemas CREA e Mútua.

Projetar e desenvolver fluxos de autenticação e autorização de usuários usando integração com gov.br (e-Gov).

<b>Problemas Relacionados:</b>

Fecha #12 (Implementar fluxo de registro unificado)

Fecha #15 (Integrar com gov.br para validação de dados)

Fecha #21 (Estabelecer conexão de API com sistemas regionais do CREA)

<b>Link de acesso a apresentação:</b>
https://docs.google.com/presentation/d/1cPM7D6umgpYF8BRyPt0o6Q7vIp1Wpdgs6ycyzdsW0Hw/edit?usp=sharing

<b>Testes:</b>

Endpoints de API totalmente testados para registro, validação de dados e integração do sistema CREA.

Testes de unidade escritos para garantir a funcionalidade da lógica de registro principal.

Este commit representa um passo importante para atingir a visão do Conf-ID de um sistema de registro simplificado, eficiente e seguro para profissionais em todo o Brasil!
