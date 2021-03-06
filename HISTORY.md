## 0.2 (unreleased)

* Implemented `id` public property for `PydanticDBMixin`. Updated *db mixins* and their tests. PR #17 by @i8enn


## 0.1.6 (20.01.2020)

* Fix arguments type in `update_many` method from `PydanticDBMixin`. PR #16 by @i8enn


## 0.1.5 (18.01.2020)

* Implemented `update_many` method in `PydanticDBMixin`. PR #15 by @i8enn


## 0.1.4 (30.12.2019)

* Allow to Mongo DB connect with default system settings and Unix domain socket. PR #11 by @hongquan


## 0.1.3 (10.12.2019)

* Implemented of set to field Pydantic model instance if field type is Pydantic model in reload method. PR #9 by @i8enn


## 0.1.2 (09.12.2019)

* Added json encoder for `ObjectIdStr` field in `DBPydanticMixin`. PR #4 by @i8enn
* Changed PyPi token in Travis config


## 0.1.1 (08.12.2019)

* Updated stage run rules in Travis config. Updated `setup.py` PR #3 by @i8enn


## 0.1.0 (05.12.2019)

* Implemented singleton interface (`MongoDBManager`) for mongodb connections. PR #2 by @i8enn
* Implemented `DBPydanticMixin`. PR #2 by @i8enn
* Included Travis config and implemented deployment to PyPi. PR #2 by @i8enn