📌 Deskripsi

Service backend untuk mengatur workspace, menentukan siapa saja user yang bisa mengakses aplikasi Money Management.

⚙️ Tech Stack

Java Spring Boot

🔗 Integrasi

Digunakan oleh fe-workspace-management-mm.

Terhubung dengan be-rbac-mm untuk hak akses.

📝 Catatan

Data workspace harus multi-tenant friendly.

Harus ada validasi agar satu user bisa masuk ke lebih dari satu workspace.

🏗 Arsitektur

Microservices: expose REST API.