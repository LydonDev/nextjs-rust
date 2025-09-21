## Next.js & Rust Backend Template

A minimal template with a Next.js frontend and Actix Web Rust backend. Easily add routes in `src/backend/routes` and register them in `src/backend/handlers/register.rs`. Configure backend port, CORS, and version in the `.env` file.

### Setup

```bash
# Clone the repository
git clone https://github.com/LydonDev/nextjs-rust
cd nextjs-rust

# Install frontend dependencies
bun install

# Start frontend in development mode
bun run dev

# Build Rust backend
cargo build --release
cargo install --path . --force

# Start backend
backend

# Build frontend for production
bun run build
```
