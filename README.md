<h1 align="center" style="border-bottom: none">
    <img alt="Azure" src="./img/azure.png" width="300" height="200">
</h1>

<p align="center">Acesse o <a href="https://learn.microsoft.com/en-us/azure/?product=popular" target="_blank">site oficial</a> 
para uma documentação completa, exemplos e guias.</p>

---

# Identidade, Acesso e Segurança

**Autenticação**  
É o processo de verificar a identidade de um usuários ou serviço que está tentando acessar um recurso ou serviço garantindo que
apenas usuários e serviços legítimos tenham permissão para acessar recursos específicos.

* ```Azure Active DIrectory(Azure AD)```  
    Serviço de gerenciamento de identidades e acessos baseado em nuvem que permite autenticar e autorizar usuários e serviços em aplicativos e recursos do Azure.

* ```Certificados e Chaves```  
    Permite que aplicativos e serviços se autentiquem usando certificados X.509 ou chaves de autenticação(chaves de API) para acessar APIs e recursos protegidos.

* ```Identidades Gerenciadas```  
    Para recursos do Azure, como máquinas virtuais ou aplicativos em execução na plataforma como serviço(PaaS). 

* ```Autenticação Federada```  
    Permite que os usuários usem suas credenciais de identidade existentes, como contas corporativas ou de rede local, para fazer login em aplicativos do Azure. 

**Autorização**  
É o processo de conceder ou negar acesso a recursos ou funcionalidades específicas depois que um usuários ou serviço foi autenticado. Tudo é controlado por meio de políticas.

* ```Azure Role-Based Access Control (RBAC)```  
    Permite atribuir funções a usuários, grupos ou serviços para controlar o acesso a recursos específicos.

* ```Listas de COntrole de Acesso(ACL)```  
    Utilizado para recursos de armazenamento, como contas de armazenamento e blobs. ACL's permitem definir permissões específicas em nível de objeto.

* ```Service Principal```  
    Os serviços podem se autenticar e obter tokens de aceso para acessar outros serviços do Azure, seguindo práticas seguras de autenticação de serviço a serviço.