# Ansible Learning Notes

## Week 1 - Getting Started
Starting my Ansible journey with web server automation.

## Concepts to Learn
- Playbook structure
- Modules (apt, copy, systemd)
- Variables and handlers
- Inventory management

## Progress
- [x] Set up GitHub repository
- [x] Create project structure
- [ ] First successful playbook execution

## 🎉 Premier Succès Ansible - 2025-10-03 17:37

### Playbook exécuté avec succès !
- ✅ Nginx installé automatiquement
- ✅ Service démarré et activé
- ✅ Page web personnalisée déployée
- ✅ Handlers fonctionnels

### Commandes utilisées :
```bash
cd projects/week-1/web-server
ansible-playbook --syntax-check playbook.yml
ansible-playbook -i ../../inventories/local.ini playbook.yml --check
ansible-playbook -i ../../inventories/local.ini playbook.yml
```

### Résultat :
- Serveur web accessible sur http://localhost
- Page affichant: '🚀 Success! Ansible configured this server'
- Service Nginx actif et fonctionnel

### Prochaines étapes :
- [ ] Personnaliser davantage la page web
- [ ] Ajouter la configuration SSL/TLS
- [ ] Créer un template Jinja2 pour la page
- [ ] Ajouter le monitoring

