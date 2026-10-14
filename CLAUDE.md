cat > CLAUDE.md << 'EOF'
# Projet : nettoyage codebase MATLAB

## Règles
- Ne JAMAIS modifier un fichier sans proposition préalable validée par moi.
- MATLAB n'est pas installé sur la VM : ne pas tenter d'exécuter les .m.
- Un commit par lot validé, message clair en français.

## Phase en cours
Phase 2 \u2014 inventaire en LECTURE SEULE. Aucune modification de fichier.
EOF

git add CLAUDE.md
git commit -m "Ajout CLAUDE.md : règles de travail pour Claude Code"
git push
