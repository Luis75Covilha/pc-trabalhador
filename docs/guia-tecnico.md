# Guia técnico de implementação

Este guia resume a lógica técnica do projecto **PC Trabalhador**.

## 1. Preparar o computador

1. Usar um computador portátil antigo, mas funcional.
2. Garantir que o carregador está estável e que a máquina consegue arrancar sem intervenção humana.
3. Configurar a BIOS/UEFI para recuperar automaticamente após falhas de energia, se essa opção existir.
4. Configurar o Windows para iniciar sessão automaticamente, quando o contexto de segurança o permitir.
5. Impedir suspensão, hibernação e encerramento ao fechar a tampa.

## 2. Limpar o ambiente Windows

O sistema deve ser previsível. Para isso, convém:

- remover programas desnecessários;
- desactivar notificações e janelas emergentes;
- evitar actualizações automáticas em horário de execução das tarefas;
- manter apenas as aplicações essenciais;
- programar reinícios regulares.

## 3. Instalar e configurar o RoboTask Lite

O RoboTask Lite funciona como centro de comando. Pode abrir programas, clicar em botões, detectar janelas, executar scripts, copiar ficheiros e activar tarefas por horário.

Cada tarefa deve ser testada manualmente várias vezes antes de ser deixada em execução automática.

## 4. Sincronização na cloud

Para tornar os resultados acessíveis, os ficheiros produzidos pelo PC Trabalhador podem ser guardados numa pasta sincronizada com Google Drive, OneDrive, Dropbox ou outro serviço equivalente.

## 5. Manutenção

Recomenda-se:

- reinício diário automático;
- verificação periódica do espaço em disco;
- limpeza de ficheiros antigos;
- acesso remoto para diagnóstico;
- monitorização de falhas por e-mail ou outro alerta.
