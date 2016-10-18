Qt SQL driver plugin for SQLCipher
==================================

This is reiplemented plugin from https://github.com/sijk/qt5-sqlcipher repo
to build against Qt 5.7 libs (internal sql plugin implementation changed).

To build it together with other plugins:
- simply put the plugin project files to the `qtbase/src/plugins/sqldrivers/sqlitecipher/` dir;
- add `SUBDIRS += sqlitecipher` to `qtbase/src/plugins/sqldrivers/sqldrivers.pro`;
- build/rebuild plugins; 
- after that check `qtbase/plugins/sqldrivers/` dir, `sqlitecipher` should be there.

## Dependencies

- Qt >= 5.7

If you have any questions, look through original project READMEs or feel free to ask me.
