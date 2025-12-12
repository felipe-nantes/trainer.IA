# trainer.IA
MEU APLICATIVO MUITO FODA DE IA QUE MONTA TREINOS PERSONALIZADOS AUTOMATICAMENTE

# Trainer.IA

Trainer.IA é um WebApp (PWA) que utiliza Inteligência Artificial para gerar treinos hiperpersonalizados com base em:
- Tempo disponível no dia
- Objetivo físico
- Grupo muscular desejado
- Estado físico e mental
- Equipamentos disponíveis na academia
- Experiência do usuário


O sistema adapta automaticamente treinos para:
- Academias completas
- Academias simples com poucas máquinas
- Treinos de calistenia
- Treinos em casa


## 🚀 Tecnologias
- Next.js (ou outro framework web escolhido)
- Serverless Functions
- Banco de dados PostgreSQL (Planetscale/Supabase/NeonDB)
- OpenAI GPT-4.1 / GPT-4o
- Auth (Clerk/Auth.js/Supabase Auth)


## 📦 Estrutura do Projeto
trainer.IA/
├── src/
│ ├── app/
│ ├── api/
│ │ └── ai/
│ │ └── generateWorkout/route.ts
│ └── lib/
├── prisma/
│ └── schema.prisma
├── README.md
└── .env

## 🔑 Variáveis de Ambiente
Crie um arquivo `.env`:
OPENAI_API_KEY="sua-chave" DATABASE_URL="url-do-seu-postgres"

## 🧪 Teste da API de IA
Uma rota serverless de exemplo (`/api/ai/generateWorkout`) já está incluída para demonstrar como chamar a LLM.


## 📄 Licença
MIT
