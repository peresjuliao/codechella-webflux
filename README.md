# codechella-webflux
Projeto CodeChella - API Reativa com Spring WebFlux (Curso Alura)
## 🎪 CodeChella - API Reativa

Projeto desenvolvido durante o curso **Spring WebFlux** na Alura.

### 🚀 Aula 01 - Primeira API Reativa
- ✅ Setup do projeto com Spring Initializr
- ✅ Configuração PostgreSQL + Docker Compose  
- ✅ Migrations Flyway (tabela eventos + dados)
- ✅ Entidades: Evento, TipoEvento (enum)
- ✅ Repository reativo: EventoRepository
- ✅ Controller com Server-Sent Events
- ✅ API funcionando em http://localhost:8080/eventos

### 🛠️ Como executar:
1. `docker-compose up -d` (PostgreSQL)
2. Execute `CodechellaApplication` no IntelliJ
3. Acesse: http://localhost:8080/eventos

### 🎯 Tecnologias:
- Java 21
- Spring WebFlux
- Spring Data R2DBC
- PostgreSQL  
- Flyway
- Docker
- Netty (servidor reativo)
