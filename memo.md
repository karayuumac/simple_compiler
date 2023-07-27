# メモ
`if ( <条件> ) if ( <条件> ) <文>` else <文>  if ( <条件> ) <文> = <文> とみるか、
if ( <条件> ) `if ( <条件> ) <文> else <文>` とみるかの2択（ぶら下がりelse問題）
これの解消のため、RPの優先順位をELSEよりも下げる.
-> conflictの解消
-> https://kenichi-asai.github.io/lex-yacc/