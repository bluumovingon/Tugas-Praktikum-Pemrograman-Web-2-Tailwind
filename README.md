
Nama: Muhammad Ariandra Anugrah
Nim:2411102441273

# Tugas-Praktikum-Pemrograman-Web-2-Tailwind

1. Mobile-First Approach
Desain dimulai dari tampilan mobile (320px) kemudian dikembangkan untuk tablet dan desktop menggunakan breakpoint Tailwind:

Default (mobile): Layout vertikal, grid 1 kolom
md (768px+): Layout horizontal, grid 3 kolom
lg (1024px+): Layout expanded, grid 4 kolom

Pertanyaan Reflektif
1. Mengapa memilih Mobile-First Approach?
Mobile-first memastikan core functionality bekerja pada device dengan constraint terbesar (layar kecil,
bandwidth terbatas). Ini mendorong prioritisasi content dan progressive enhancement untuk device yang
lebih capable.
2. Bagaimana Tailwind CSS mempengaruhi workflow development?
Positif:
Rapid prototyping dengan utility classes
Consistent design system built-in
Reduced CSS file size dengan unused class purging
Inline styling yang readable dan maintainable

#Keputusan Grid-cols/Gap di Tiap Breakpoint

alasan setiap grid col/gap setiap breakpoint
Single column: Content mudah dibaca tanpa horizontal scrolling
Minimal gap (4px): Menghemat vertical space yang terbatas
Touch-friendly: Tap targets lebih besar dan mudah dijangkau
Bandwidth consideration: Hanya load satu image per viewport

#Pemanfaatan Utility Responsive untuk Masalah Mobile Layout
Permasalahan 1: Profile Header Layout(Desktop horizontal layout tidak cocok untuk mobile)
Solusi:
flex-col : Mobile vertical stack
md:flex-row : Tablet+ horizontal layout
md:items-center : Center alignment untuk horizontal

#Trade-off: Utility Classes vs Component CSS
#Kelebihan utama menggunakan pendekatan yang sudah diimplementasikan
1. Rapid Development
   styleing gampang tanpa class naming
2.Memiliki design yang konsisten

#Kekurangan
1. Memiliki isu pengulangan
2. Kustomisasi yang terbatas
3. 

