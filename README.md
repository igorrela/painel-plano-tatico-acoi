# Painel do Plano Tático — ACOI

Página do painel de acompanhamento do plano tático da ACOI (unidades Corp, Home e Projetos).

Este repositório contém **apenas a casca da página**: layout, textos de interface e o código
que fala com o banco. **Nenhum dado do plano está aqui.** As tarefas, responsáveis, prazos e
status ficam num banco Postgres no Supabase e só são entregues depois do login, para e-mails
previamente cadastrados. A chave que aparece no HTML é a chave publicável do Supabase, feita
para ficar visível: sozinha ela não abre nada, porque todo acesso passa pelas políticas de
segurança em nível de linha do banco.

Editar o painel exige perfil de editor. Os demais cadastrados têm acesso de leitura.

Fonte do plano: Plano de Ação Consolidado do PMO (G4 Consulting).
