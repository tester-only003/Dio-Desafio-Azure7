# Microsoft Entra ID e Domain Services

## Microsoft Entra ID
O Microsoft Entra ID é o serviço de gerenciamento de identidades e acesso baseado em nuvem do Microsoft Azure.

- A Microsoft está, aos poucos, desativando o nome “Active Directory” por Microsoft Entra ID.
- O Entra ID é um serviço de diretório que vai permitir que seja feito o Login, tanto os aplicativos de nuvem da Microsoft como os aplicativos que forem desenvolvidos.
- Através do Entra ID é feito o controle de identidade.
<br>

#### Responsabilidades do Microsoft Entra:
- Autenticação (os funcionários entram para acessar os recursos).
- Logon Único (SSO - Basta se autenticar em uma única aplicação que será validado o acesso para as demais aplicações).
- Gerenciamento de aplicativos.
- Negócios para Negócios (B2B).
- Gerenciamento de dispositivos.

   <div align="center">
    <img width="653" height="280" alt="Microsoft-Entra1" src="https://github.com/user-attachments/assets/45e0c424-e6eb-401a-bcc5-25a63b5c39d4" />
   </div>
<br>

#### BENEFÍCIOS:
- Benefícios dos serviços de domínio baseados em nuvem sem gerenciar os controladores de domínio.
- Execute aplicativos herdados (que não podem utilizar os padrões de autenticação modernos) na nuvem.
- Sincronizar automaticamente a partir do Microsoft Entra ID.
<br>


### Autorização

- Determina o nível de acesso de uma pessoa ou serviço autenticado.
- Define quais dados eles podem acessar e o que podem fazer com eles.
<br>


### Autenticação Multifator (MFA)

Fornece segurança adicional para as identidades, exigindo dois ou mais elementos para a autenticação completa.

   <div align="center">
    <img width="692" height="190" alt="Autenticação-MFA1" src="https://github.com/user-attachments/assets/f976a22b-2e6c-440c-84d4-474b176aef5d" />
   </div>
   <br>


   <div align="center">
   Exemplo: Windows Hello (Biometria - reconhecimento facial)
      
   <br>   
   <img width="237" height="220" alt="Windows-Hello1" src="https://github.com/user-attachments/assets/ab912948-1bda-4c43-afdd-9eaea2a520d7" />

   </div>
   <br>

### Autenticação B2B (Colaboração B2B)

Neste cenário o ponto chave é que o serviço (pessoa ou dispositivo que precisa fazer autenticação) está fora da sua organização.
      
   <div align="center">
      <img width="458" height="347" alt="Autenticacao-b2b-1" src="https://github.com/user-attachments/assets/7151eb78-5d10-4785-9fef-18da8515887d" />
   </div>
   
   <br>

## Acesso Condicional
Leva em consideração os seguintes aspectos:

- Associação de usuário ou grupo
- Local do IP
- Dispositivo
- Aplicativo
- Detecção de risco

> Com base nas informações acima o acesso é autorizado ou negado.
<br>


### Controle baseado em função (RBAC - Role Based Access Control)

- Gerenciamento de acesso de granularidade fina (acesso específico apenas para a função executada pelo usuário, dispositivo).
- Divida as tarefas dentro da equipe e conceda somente a quantidade de acesso que os usuários precisam para trabalhar.
- Habilite o acesso ao portal do Azure e o controle de acesso aos recursos.

   <div align="center">
      <img width="446" height="414" alt="RBA-1" src="https://github.com/user-attachments/assets/6d1be699-3447-43c8-84ac-a48632d78489" />
   </div>

   <br>

<div align="center">

   **Dentro desta hierarquia quanto mais acima é feita alteração, o que está abaixo vai herdar.** <br>
    *Os permissionamentos são herdáveis.*
</div>








