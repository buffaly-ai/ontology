# Temporary prototype registration

TemporaryPrototypes assigns temporary IDs and maintains cache/name/ID registration. It does not infer lexical nesting from dotted names. The ProtoScript compiler explicitly calls InsertNestedParent when it declares a lexical child, where both endpoints are known. This removes the former whole-cache reverse scan from every value insertion. Reset/reload and registration semantics are unchanged. Direct callers of the explicit nested relationship API remain supported; generic name insertion does not create that relationship.
