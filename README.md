body {
  font-family: 'Helvetica Neue', sans-serif;
  margin: 0;
  background: #fff;
  color: #111;
}

header {
  text-align: center;
  padding: 2rem 1rem;
  border-bottom: 1px solid #ddd;
}

.slogan {
  font-style: italic;
  margin-top: 0.5rem;
  color: #444;
}

.intro, .mision-vision, .galeria, .contacto {
  padding: 2rem 1.5rem;
  max-width: 900px;
  margin: 0 auto;
}

.mision-vision {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.block h2 {
  margin-bottom: 0.5rem;
}

.galeria .grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5rem;
  margin-top: 1rem;
}

.producto {
  text-align: center;
}

.producto img {
  width: 100%;
  border: 1px solid #ccc;
  border-radius: 8px;
}

.btn {
  background: black;
  color: white;
  padding: 0.75rem 1.5rem;
  text-decoration: none;
  border-radius: 30px;
  display: inline-block;
  margin-top: 1rem;
}

footer {
  text-align: center;
  padding: 2rem 1rem;
  font-size: 0.9rem;
  background: #f5f5f5;
  margin-top: 3rem;
}
