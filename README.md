# Cours d'analyse #
## Description ##
## Implementation ##
- codage/programmation
- test
- integration 
- analyse
- conception

```mermaid
flowchart LR;
    A(analyse)-->C(conception);
    C-->D(codage);
    D-->T(test);
    
```

## Source Control ##
La gestion du code source.
On utilise git, mais il y a d'autres systèmes (subversion, mercurial).

Le flux de developpement:
```mermaid
flowchart LR
C(code)
R(local repository)
G(github)

C--commit-->R;
R--push-->G;
```