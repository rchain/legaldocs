# Ballot Deployment

DEPLOY ID (signature) "935b76bd04683fc0018267df9b5f6868d351eef77d24a451c5505d9e76d4d05a19956ee74a5f1c6ebb16662e69f3b03e8789fb532fe901c3addcf30a0002fc741c" \
(URI, rho id t45o9iwfchgt1e7qsidga45r4wqy58iyexct8yyyc7xdwisdesquts) // cost: 185025

```
new return(`rho:rchain:deployId`),
  insertArbitrary(`rho:registry:insertArbitrary`)
in {
  new uriCh, valueCh in {
    insertArbitrary!({
  "Validator Rewards": {
    "shortDesc": "RChain mainnet is moving towards decentralization and needs 3rd party validators and all REV holders to help secure the network. The membership resolves that RChain Cooperative mint all validator rewards. Minting will be on an asymptotic schedule similar to Bitcoin. The total validator rewards minted will not exceed 100M REV over the life of the protocol. (See supporting illustration below)",
    "docLink": "https://github.com/rchain/board/tree/master/2022/06-29#1-validator-reward-mint-policy-iob-2022-01",
    "yesAddr": "1111cxvUtMNeNHbDQa4R2NTZ3VJA7jMVzZ49ekHWTkQKHfN8qMwka",
    "abstainAddr": "1111gwzeJWGutj4bFQjD8idF1mAnorSkLByr5gGGH1dAMs2GzG3pB"
  },
  "Unburn REV": {
    "shortDesc": "The membership resolves that upon the sale of 60M REV the Coop will unburn the tokens that burned at the outset of the project. The unburned REV will return the total token supply to 1 billion REV.",
    "docLink": "https://github.com/rchain/board/tree/master/2022/06-29#2-unburning-rev-tokens-iob-2022-02",
    "yesAddr": "1111QcXmnnd6dgAWfu2qZtWYDLuRubR23tbryrnmRyWGNU9ciTABD",
    "abstainAddr": "11113464E9vZByke2atuY7cbVruCp3cjjzL1Ykwfm1AjyWNXGJixm"
  }
}, *uriCh) |
    for (@uri <- uriCh) {
      return!(("URI", uri))
    }
  }
}
```

# Voter List Deployment

DEPLOY ID (signature) "223cf5fb54717e34ab936b1ade812a8911e603f8c4963e64fadfd53321890c7814ef2bfe6be1501fe88ab146f53e47e730a3e41cd5a43333f726806d10af1f841c" \
(URI, rho id 7ep86cizsj5jd7akf3641cyd8t89xuuzw6tfnyxon7nedc144pwshj) // cost: 778970


new return(`rho:rchain:deployId`),
  insertArbitrary(`rho:registry:insertArbitrary`)
in {
  new uriCh, valueCh in {
    insertArbitrary!(Set("11111KJmBfZXsAtJ7o51XvaPC1xaqwq9SPnjkYCqtQTiovF1GAbLK",
"11111LHTzJGYkvmr8zK4FwNTy1Bbrmu5QnS91L13Azb6xNEu7a6gb",
"111121igMDfzxSyEnT81TJ5sAv59Vh3cFEhLhV3UvgHgvyBebxkSKe",
"111121MVmEMKDNj6DnDCp5VEBqj5ZQ3y5Pi28D9CCwPMnu7xqe1its",
"111121YPNEg2JFQHRCd7jKcMKd7kY1D2XwvYyZvmNfvJa7MQELagpy",
"111123ZgLdhsE5MLmNwimQUgwR5PLC6wWhkL1F13TJUuhCP7PASKsc",
"111124hDh8mVEmH3PrSpY1W3FayMsy6DXgMMmqzrxuucFXLamGsww9",
"111125DL4Kis7Q6E1c1LtSS8VPQbfK9wk1b84jGnwP9HLxg275KR7H",
"111125Pn3p9i2rNc3A14gsJ6xETkbTk3ZBRNxaEfTKiiJH5MBKjCeZ",
"111126bwy4euigHSeN8uzHyZJq5THCDBZEvSn61rCMUQkzZjbPBmKA",
"111126iENYgWrfiwfSTRU5q8iUcdh3jjobS1y6j6AvZhK3g3UGwUmw",
"111128kPWggtHPrq1iaKHjxLVF3gPRQWok2dRCZXS5SPnS72KBqCVw",
"111128qWRFJu7cBgy9a8ir8VSSoLzMzJRfrUvJUjrgU6rEQ4a1EFqi",
"111129kduQXToN8tTYtPBtHzLBQNobZycDVhjsp8Ayo6qEKgm8EwzP",
"11112AQiVPXmASU2SGnS2qCQN5p3QyEcp2mZTYn5KmNwEKEswfuRp2",
"11112bGPwBVnMNkcc4eHN6ZGjTB6fwoLxQGrtbTs44NP41ERfSu4GM",
"11112CHQsTAAcGUuM8ydA1dVZmzdubGngojPSFPSoEwfd2mcAszKqi",
"11112CiSr2g21zE72vteksS7RgbCcisRHz7ioZQcLKGDnuCjjR4PwS",
"11112ctdhvFgzmfhbga4X2DtzRuso9WwsMEVHziTmX4snPWU1XW6XL",
"11112DBvhzJioVEGkXPeXGx1EDd5LLVRP2GsQvrtL29XPurbbjdWMf",
"11112deNsfm4PQaWXDqf9qEgy1gjqNzQ5XBkuLyG4Qm6U9ECjmoWGb",
"11112DKNQzG8C6TJMh35YPrTt6xv8L9xBftMoUiNqA19BWMoEsjpob",
"11112eA5w81vfE9BwziWkdjWq443qyYuanEScnRirdqdEXLe36zSb3",
"11112eYs4DyFCG5WiexDwuGXXxMpaASfPmoZDHHtsLCP2i9X1AfsXg",
"11112fCdvChKtEuzTRVY7VtU89mg1qqTHRnQFbbZheRw5mtqGRB9fM",
"11112fEZ7WSwLob9zSm2QQVzJ8Pmgsoazk1NNzcuRz7M1oRjoZSgm",
"11112fma4Rz7irA5YEkgAi8Q7qcSZ3C7Jho6fhKR6mkMvKrwZbPbSC",
"11112GAY9Fd8i7uvm6MY2rpm6j63JLVJdS1EnGe4zivsKKCpcLfy2K",
"11112gKZNgifMCwxYhwkPdacw7W3xPkbRH5QDsJXgLcDZtioJsJefE",
"11112GNwMdEQiKwYVgKkuNo6eWuN7n5viyC18qfUeey7B2wvcVL6eG",
"11112gS2NiP3H7yEwsoEVnEdbMtoF48V56sz7LweWtPeE48XnwruEG",
"11112hAq6VEmDJAoopQQZoEomSWzodZMWgme4dGzwM7oeVP24fWBm4",
"11112hC2bxFbajN7bNbgL4hEDbYyQrEyd14WYACDYBT1cqrdc2yuCX",
"11112HccK2NxAzjMMhTA2FvD7RZSzChSm6vSYkYAxeHjtGGcax8tjB",
"11112hK74u4pKGxdSVWuKtDtEbDFwVUujDemg5RVA7BddfTvPgcTbW",
"11112HMarTvkoZGrqveWvAoZX2j5kd8Xi2ssudytwyKqY7Qc86MAQb",
"11112HstFJhwzEurKPdbKLtVt3xm9wKT8mygizRrz1VQAmaVziKTa1",
"11112iHix54S6masBuqh7FXwuBTJX7qATCYF4Koh4qkqFP8DTdt8fD",
"11112ik7DdbuiKWshbAhgiuvHZdbbiFDELJxfv9C1QaWv8jZZvhCp",
"11112iLWCmdU4qjuVvEkFpCXUt7aB6xXoNvc5xHERecqH4tKL9JEmL",
"11112JB17w8rPnwaeH1RfFdUguD7cVKvoi6QJcLmDVe6aRtMu2KmtE",
"11112JBboUMLRzcWNm6Wzox7qDuCbW6f5XZuMu94eejJNocsDRfWqx",
"11112JfTQuUurLxX4E4mDu3gUGzqQHwj7LKrDn9H5WTvDeZPDchWQW",
"11112jqy1nfT5RFgpEPmUDho9sGBRQsufQG9raLXwk4RyrjezdjzrJ",
"11112JUDhe4RHoPDTtXZP9re42nxYbDC2v8u2Ls7fgd9HQywQcLZTm",
"11112kbhGfxG8hndEBMptg8SdMkjPaH1z7n5F26AaRoPQHaAfeURSM",
"11112ko4mMKPSVahGkyutwrKuaG5YufEyHXZHtmSbgfLpNuw6inpp7",
"11112LAbGNJ12V8VAq1FKZNP1o5BBK9bPwPdsoNmMxLMVEYB2vjzkX",
"11112MAVSMc6McnQBNVA7iUcUfnk8hxvNHMDEZAGfKPx2JSr5ZBN1E",
"11112MB3XW1MqfCRc6VwWhrx9vsCuLqR6YUBfhqKPsgj4aQPccECsc",
"11112MbAp4s4pqs1zRFe1kGxLqAYALSuhP9GtwEWHsh2pn7JF7FazF",
"11112McdDTjGnb95VPics1Va97FbyBdE3NrA2qf2BsYXRFuEPE1u13",
"11112moXRwze8ec4rzFU5iiVgpmRF3XpPUy2meu3TS2vVAWjZMWAac",
"11112NEtCboyfpckaoht3fDikuHXCLeFTkkWeoQjKydtDAPmpKgULB",
"11112no9aFFEM3R5SGepyvbfbzpWFQ1wfJhdUtynFh9cC39kKWHTBJ",
"11112ouNMpMXqGFieVTd5AtTie4CuEYw9bVQtYR4AJEJoVnMaK6GMN",
"11112P4ZoRKkK6Rn3A5mu7EYKByKJEQyg8Ab8CLG33eWZArLSpeUE4",
"11112q5Y8MaoA7c1omjVthx4AQJjboAZCLhwcPcYYYUVUr6Q8ikWTR",
"11112QRYCsRpBnFWNfVewtCowhLGXuMimvqaVzmp5opmR8yNWBxmg6",
"11112qx7RQDp8Um2rTwFLfjQF38egRYdb4jXMiPvim4HPo77PpTdDu",
"11112rnK23AsoGjiforbgcsk7Dy9cCAsqCmt4ty95xNMKEvW9ckzgC",
"11112RsaYgPLWNjSqGy4DVv3XLWVgmBxQXX5JiMN7MqHL6wnAuUEMQ",
"11112sVm2qR8s69B6X6HTb51vqatkZNSbEz1hZSEvZW7pAHRNMmgAG",
"11112UH8qmJYYdTXa9iFZQ6vHuG4eRQ9m6GcZJRsqxm2dZPvHEczQi",
"11112UZ4kdUFnCywb5h6gxzKNAx48QgzePkFVdoNDzK5n81HJGyGDR",
"11112vCd9h138YoFohhK9CsheDjPLnJthBNqFKyFJTx53xUf2a9B7w",
"11112whBHoMfSrMrvgFtwG7MuQ36tNEkviSeAT4gdz2KyGBLodwEpb",
"11112wMkPc3zyqdGpvLwfgjKFUzWU4i81WmnA2Fr7syMPVSskXy8TG",
"11112WPR87aGqkdTmEzkS287Hnc5mFZ3NHdMNp8DwfExDPvpAoJCKE",
"11112WZWHJkyMuZJ1cDsAYDEGbgxnBM49poWHST5ZDeDA33MvCGqEG",
"11112X4g24XLfKT4J5yVVyeArX38H9g3Xase1xqpevfY2s7JpqN67g",
"11112YKpnwtjZfzxZKQh2jAkQUWHF8vHYniE6E5FytXhHkmfFgLbso",
"11112ZCnHkf13hbEpAtLYZwPHAwMpyEJPC5vmXL8W6hxsdQDyAcvXk",
"11113eQV5g1SoXfTwh8x4dy4127SFX1ux59vHp8ocJoQnDVwu4Rn9",
"11114i7p7gREAiuwTWrjEZgXHJ653iLYzdZxNxufVxhechs1sB6jT",
"11114ZPx5GdMvKUNF61CPNbSWJgTpU1sqd47tecprZKRoTR9qRze2",
"1111669Qwk3Y8RqqKLUaSU8EU5agsFrb7NPtJiaVf7snXz3Nvc5mn",
"111166ep8dTrtJLPnQYgcHGgi33NrAAftZQhUEAKzqnkNb82qewMe",
"11116Dit619d9zzVNkZpe4tZwrVh8cmqWomLiRfXrfEvAMKMcuaBD",
"11116MVrUYWPvRyemkX2C7ijVepv4fhx4wQ4zxcv23Nf5VS2cHz3j",
"111177afthwRzA7Axcdiohdu3aj5zd8g1NR223iyfcvXnKUBrEqKf",
"11118d7YfaoW9Lw8niuPzGKpQWERVRGhXHLAJVdWpxznJr5JHZM9M",
"11118LvNtquUG1HA45qyi36Mtu8ob8p2TY5XmnkkomkjMsRyuBjgb",
"11118US5E6dqNE13fYaDdMSnUyGUevAa8QF5GdZoVkQZsZV4uqYw3",
"11119GD7YGudKnYcin2SBjKxghHpQmbDvvFz5vrRTYRu4hhG5jc9G",
"1111AmgAXXLpEbxRtuWLW8stLDgAUF2KzvwLiuvZ5zYVbekSRPxja",
"1111b9zRFBdd9zgqCkik73FoPhDsj2snYpudA5zouRdedpUB74g3o",
"1111bdi15Rd1Q2JVmEka6qhRY49JHeXXsMNXr1GtV2KngMGPWVc9s",
"1111bvUb1t22SX9PbHtiDhrfbsdHyi92FkWBNk59BmWtTC5bkLB8B",
"1111C2DjJtKkDxkgoZUGPzcpzMDRq6T5Zjg4cdn1A2QnY7hK7AGYt",
"1111degtGcnFpNVDTb8ivbGp4NybLkN7oHrQpw81TX626L9h817XC",
"1111DicjQN6xPnz7tEp7YMVk34Q4ERi7YDA5ckdD3ZLwtwqGt6dzV",
"1111dj47kA1oQPvBnpnaAhfuYf8XcV8ugXU1GG5ZDQnZDCd8v5MyA",
"1111dnDgG4eGtj2hYKDg3XzWBD9T5r8n33YBvWRqD6jPKE8yE3JmL",
"1111e16ZdvYWMHQvGn1aQ7RRxUwkUpucTeRMz1s6Z6T9iYaW9anib",
"1111EELSnP7qwPJQbonTAMEoweXhZ7ZCXyypufDZjrY1p2QJsPfBN",
"1111erDNb7uqVSXwziiG55egjqVGV49p97oAPgij4XadohkSy2tTX",
"1111g66xLzErjnfVW1X7fvW38vfANf4UARJ1aKpLLVVJBXPZqGYKz",
"1111gq5h2WT1sMkPkJ2FHM8aEyUYqpYDb3mcyKmVBth6NNK5u8cTJ",
"1111hAJfwZ6rhSfJESHvoU2xpDodtTBucuZrrFre6nGuJAMub8uvo",
"1111i35pNcTVgH1JoJbmporZ3XaVPeCvfThBYUBs35MDZEQSLARYP",
"1111iP46vqja2qGyo5V9W6xUG4UJwG4yg4YHKh8VcNjiuz1h7qkvm",
"1111J5bVLwMGNroxr9DCQguJnzWR74o4H6Tb4rakexoHSzZcow47r",
"1111J8uYQC3UgKV4XDurbhzbF2Prvqy7DwF3dt81gufeVJHTPBHYQ",
"1111jaRVMx3XtVPSnR3U5S6FxEGDtKzRsMDvfitnMBJtRq3jF7doo",
"1111jcXkeoarLSseKyEhfNF5jUMq1oKxRPa25giDWcfEYwvDbUtdZ",
"1111Jdn7sADM1v5uoHBxk8YGQhPYL9certCyLMAQqW25pTQe6CZpS",
"1111K4Qq9WGTVe6F63G8TUBYPuMDwcnVe1no7oDf2HToBJHr5BmtZ",
"1111k9SCoqBJBCiyruirPRxbnsEn9oS5B1H93DJ8hYRLZ8TsqYgMX",
"1111kHePDtoSroAKZ9EP591HHBjpcmestcV5F6RXBgmrDF5jUTUFY",
"1111kJAuuGGtMah3zugMYqXiZmJUnjSgCLvo9tUMZXmwzQytQkZq3",
"1111kSHkT281oR6KbDKY5bGuUaskWBd2ibfyXPQYBGcsx7BGSzzZv",
"1111kwFVksomdFsTXuExGm9CbwKRn2ZK2SQvwKM7SvZCPxX8fT9gb",
"1111M1AfPjjFsM612NYcQQds8nN6FnRxuBSz7YdfkBhd9UsUa4BYX",
"1111maNEqcxYiwDmomZ5S4FPRZH2m8MktFeoWqgr6odgfsTEiSczD",
"1111mi9W8DBwJozihgSuhs4WGURVuCgkPqtQuhvNLCFK81XKhQsWx",
"1111mQx7bW17rJwKeYnUWAB4fN3yA1bTH4U6obRDH7dyv8mGvXSQz",
"1111MUpe7BVA8p3dnxZdxWSNiPbYijeTWphZcaR7XzPxFPXkRSeg6",
"1111NAwjKiBL7koZLLdNe8NqzrmDuv9cuGRupy9j5mDeVLZ2dZghk",
"1111nWWZYWBdDZQyPFSwP4W9uD2L2RTqegoV5sm6qy7ryntdTxXei",
"1111oCPqhRJdtr5sZHQsCxpgdeafomwPoi7wSrPL9tzMMHtDuqrjg",
"1111ojC38qJdyXJzarfpxNkhmSfcYZC37Tp5o6fkKuYxvokNkqp6x",
"1111ojMx8BbV7WLvuC9qgv1CUsggszLWcr9WmyaEyvdVrNGFfywuo",
"1111PsjS2khQ6XexeLFXFfNWpVAcF6Vx6AfRCGnxZs2QMdHkQuVW3",
"1111qbDReBTiNG2MifJtVgsree6DSNNtxFhnnc777FNeAVJtbY6Ta",
"1111QqqxPZcBLAyYw7SW2YWcNWDMJYxozNetw9SGz5DjAig6dGHKj",
"1111rtqVWhdehZXVRTBajJ9gJ8VwKfWxX8nwNVSug7SbccHRUdjZZ",
"1111sHpNqgvEPjBBgZt9u3kXfzs3TVeicNVAZcq732HNwj4Pr5pLX",
"1111t8ikk8Q7t48JXQDCssUsuJBEydFLWB6bfQcUczLFmSbLgA78n",
"1111tAVymTCnhJGaf9HhKxiPKcj413Xn64fJvAQJueCdyuZqmbc6N",
"1111THTUhXUr7zYeb5txiiwJaoGuczEgS87rMc1fgWAxaC6uQ2bQb",
"1111TJ7xQD8dPBLJEUdr5AKaBGhEWVZ7LgfsCJojegXRUSEyMqEuF",
"1111TybNY6XRRhq6mJZDUA83UEiWKf7bDgHnBHtiU7kSW1RKjzf3u",
"1111u7bAgfTVB8uc3XeMotGpPng2a7v9htV7XqhqjFrcjqqKP1MgA",
"1111UrwKfhE3CqCkkakTexaBGFuT6MCVdzqqKUoRdXugKLkj6jkEG",
"1111V1YQdAcdBodVU715TnFRhohAHyo6NqU7zppTsvDAQAbxYdKLx",
"1111v7rAsS7kcw4P649YhjSvJGhbuQTo5bT1AVov4A5sexFdNVQXR",
"1111WPcGvg68ELAfcLEpqn32AKKqTMYKCdgtH6YSQzni3SNo74yS2",
"1111WXWtHuM1ABwSnXCAn8pbvYYGq2phqhcxHTYLFfEydXixoSBfT",
"1111wyN4kmDVnPcXuK9fbJMVv9BUx2o9i8asRJ9ESXJNhXm451tu1",
"1111XUHBtSJ7SuziKb5yRb7C4TN1hjpbBZaUteembxABySKVQoWrh",
"1111XzJR2VPvEYtKngc8x2UJrjiwhPqDfyb2iEMtMdvd4pHhyvHzr",
"1111XzvxvFKQ7Pab1WSwG87ixbZsXotVGb74ZjN9aLntcKVtZCzPZ",
"1111YJckKqf729z4tryqg1bcrW6iLiY5Di1b93ejEj9FN26J7v8g8",
"1111z1GUsNiLrPr8ixSWWirqHovCUCFvDLmFuMtQSM2wJKdqPDqBG",
"1111zcCS3iriBeZ96LKtKFebDM4QuUbkAdLovc1WEewt17WiP7H8o",
"1111Zfr2UB1YXuD6zccsPhqthiik4jfQV8W8aoncbvVGtfU8QJQei"), *uriCh) |
    for (@uri <- uriCh) {
      return!(("URI", uri))
    }
  }
}
```
