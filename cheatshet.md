# --- 1. Konfigurasi User & Email ---
git config user.name            # Lihat username lokal
git config user.email           # Lihat email lokal
git config --global user.name   # Lihat username global
git config --global user.email  # Lihat email global
git --no-pager config --list    # Lihat semua konfigurasi (tanpa mode pager)

# --- 2. Menghubungkan ke GitHub ---
git remote add origin https://github.com/username/nama-repo.git  # Menghubungkan repo lokal ke remote
git remote -v                   # Verifikasi link remote
git clone https://github.com/username/nama-repo.git             # Clone repo dari GitHub ke lokal

# --- 3. Manajemen Branch ---
git fetch origin                # Update daftar branch dari GitHub
git branch -a                   # Lihat semua branch (lokal & remote)
git checkout nama-branch        # Pindah ke branch (versi lama)
git switch nama-branch          # Pindah ke branch (versi baru)