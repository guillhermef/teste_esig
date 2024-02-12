# Vulnerabilidade Open Redirect:

-- Tomcat rodando na porta 8081 # http://161.97.89.107:8081

-- Rota autenticada contendo o payload # http://161.97.89.107:8081//secret.html;@tomcat.apache.org

-- Vulnerabilidade corrigida na versão Tomcat 9.0.80 rodando na porta 8082 # http://161.97.89.107:8082//secret.html;@tomcat.apache.org

# Vulnerabilidade descoberta de informações por meio de mensagens de erro do sistema:

-- Rodando na porta http://161.97.89.107:8083/servlet

A mensagem de erro pode divulgar informações confidenciais que um invasor poderia utilizar para lançar novos ataques ou expandir a superfície de ataque. Além disso, ela pode fornecer ao invasor insights sobre o funcionamento interno da aplicação.
