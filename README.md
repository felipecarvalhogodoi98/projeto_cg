# Projeto de Computação grafica
**Alunos**
- Felipe Carvalho Godoi
- Pedro Henrique Maciel Alves
- Pedro Henrique dos Santos M.
- Jhonatan Gardioli Lourenco
- Thallys Henrique Martins

**Professora**
- Ana Paula Piovesan Melchiori

## Requisitos do projeto
- [ ] Quarto
  - [x] Parede, Chão, Teto
  - [x] Porta, Janela 
- [ ] Objetos
  - [ ] Cama, tapete, mesa, quadros, entre outros
- [ ] Objetos dinamicos
  - [ ] Usam algum tipo de animacão
- [ ] Ambiente
  - [ ] Iluminacão
  - [ ] Animacão de objetos
- [ ] Navegacão
  - [ ] Mouse, teclado
  - [ ] Colisão
  - [ ] Fisica(gravidade)
  - [ ] Selecão de objetos


## Requisitos para executar o projeto
- Instale a OpenGL Utility Toolkit (GLUT)
- Instale o pacote Miscellaneous Mesa GL utilities
- Instale as bibliotecas X11 miscellaneous utility library e X11 Input extension library
- Instale a GLFW3 (OpenGL Framework Window) 
- Instale a biblioteca **ljpeg** para codificação e decodificação de imagens JPEG

## Codigo de compilação e execução
- Compile o codigo 
```
> g++ main.cpp bibutil.cpp bibutilNoTex.cpp -o main -lGL -lGLU -lglut -lglfw -ljpeg
```

- Execute
```
> ./main
```

