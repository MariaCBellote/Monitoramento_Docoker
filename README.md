# Esse repositório não deve ser aplicado em ambiente de produção!!

A versão 3 do PMM exige a definição/troca da senha do usuário admin no primeiro acesso pela interface gráfica. Se a senha padrão admin não for aceita de início pelo pmm-client, basta acessar a interface Web do PMM em https://localhost (ou no IP da máquina), redefinir a senha do admin e atualizar a variável PMM_AGENT_SERVER_PASSWORD no compose.
