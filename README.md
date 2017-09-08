
Idea de la presentacion
=======================

1.- Conceptos de uu-parsinglib
2.- Combinadores
    - basicos
        * pSym
        * pReturn
        * pFail
        * opcional (<<|>)
        * pAny
    - derivados
        * simples
            ^ <$>
            ^ <$
            ^ <*
            ^ *>
        * secuenciales
            ^ pList, pList_ng, pListSep, pListSep_ng
            ^ pList1, pList1_ng, pList1Sep, pList1Sep_ng
            ^ pSome
            ^ pMany
            ^ pFoldr, pFoldr_ng, pFoldrSep
            ^ pFoldr1, pFoldr1_ng, pFoldr1Sep
    - especiales
        * pMaybe
        * pEither
        * pPacked
        * pChainr, pChainl
        * pCount
    - repetidores
        * pExact
        * pBetween
        * pAtLeast
        * pAtMost
    - permutadores
        * <||>
        * <<||>
        * pmMany
3.- Utilidades
    - caracteres
        pLetter, pDigit, pLower, ... , pAscii
        pSpaces
    - lexeme parsers
        pDot, pComma, pLBrace, pSymbol, pInteger, pParens, pTuple
    - idioms
    - llamadas a funcion principal
        execParser, runParser
4.- Escribiendo un parser simple para XML
    -> datatypes
    - pattributes
    - ptagged
    - pspecial tag
    - ptext
    - pxml

