## Como rodar o projeto?

* Clone este repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Execute as migrações.

```
git clone https://github.com/lucvsbraga/sistemaEstoque.git
cd sistemaEstoque
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```
## Links

[Material de Apoio - Régis do Python](https://www.youtube.com/playlist?list=PLsGCdfxkV9uqj9DwI6Y72JyvXeA-9mAjc)

