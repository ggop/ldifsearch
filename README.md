# ldifsearch

ldifsearch is a Perl script which allows you use the usual LDAP filters on LDIF files. The commandline options are similar to OpenLDAP's ldapsearch. It depends on the excellent Net::LDAP module.

Supported options include

    -f => Input file (uses stdin otherwise)
    -b => Specify base to which the filter is applied
    -s => Specify the scope (sub, base or one) 

As of now, the operators allowed in the filter are `eq`, `and`, `or`, `not`, presence and substrings. Support for <=, >=, etc is pending. If you'd like more features, file an issue!
