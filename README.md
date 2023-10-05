[English](#My-repositories)/[日本語](#リポジトリリスト)   

# My repositories
---
<details open>
  <summary><h2>Libraries / Modules</h2></summary>
  <table>
    <tr>
      <th>Name</th><th>Link</th><th>Language</th><th>Description</th>
    </tr>
    <tr>
      <td>slib</td>
      <td><a href="https://github.com/YujiSue/slib">Github</a></td>
      <td>C/C++</td>
      <td>Libraries for supporting c++ coding. There are 3 sublibraries.<br>CMake installation is available.<br>
      <ul>
        <li>libsobj <br> A basic library.</li>
        <li>libsapp <br> A library to make command line applicaition.</li>
        <li>libsbioinfo <br> A library used for my bioinformatics research. </li>
      </ul>
      </td> 
    </tr>
  </table>
</details>
<details open>
  <summary><h2>Applications</h2></summary>
  <table>
    <tr>
      <th>Name</th><th>Link</th><th>Language</th><th>Description</th>
    </tr>
    <tr>
      <td>BioInfoTools</td>
      <td><a href="https://github.com/YujiSue/BioInfoTools">Github</a></td>
      <td>C/C++</td>
      <td>Bioinformatics apps used in the <a href="https://pubmed.ncbi.nlm.nih.gov/33828169/"> article</a>.<br>
      <ul>
        <li><a href="https://github.com/YujiSue/BioInfoTools/tree/master/GenomeConverter">GenomeConverter</a>: A program to encode a FASTA format genomic sequence to a compressed binary file.</li>
        <li><a href="https://github.com/YujiSue/BioInfoTools/tree/master/GenomeExtract">GenomeExtract</a>: A program to extract the sequence.</li>
        <li><a href="https://github.com/YujiSue/BioInfoTools/tree/master/GFFParser">GFFParser</a>: A program to display the summary of gff3 file.</li>
        <li><a href="https://github.com/YujiSue/BioInfoTools/tree/master/AnnotDBMaker">AnnotDBMaker</a>: A program to make a sqlite3 format database for gene annotaion.</li>
        <li><a href="https://github.com/YujiSue/BioInfoTools/tree/master/BioAnnotation">BioAnnotation</a>: A program to make annotation of target region using the database.</li>
      </ul>
      </td> 
    </tr>
  </table>
</details>
<details open>
  <summary><h2>Plugins</h2></summary>  
  <table>
    <tr>
      <th>Name</th><th>Link</th><th>Language</th><th>Description</th>
    </tr>
    <tr>
      <td>Stack Editor</td>
      <td><a href="https://github.com/YujiSue/IJPlugIns/blob/master/Stack_Editor.java">Github</a></td>
      <td>Java</td>
      <td>ImageJ plugin<br/>
      Cut out the specified slide(s) from a stacked image.
      </td> 
    </tr>
    <tr>
      <td></td>
      <td><a href="">Github</a></td>
      <td></td>
      <td>
      </td> 
    </tr>
    <tr>
      <td>Library Measure</td>
      <td><a href="https://github.com/YujiSue/IJPlugIns/blob/master/Library_Measure.java">Github</a></td>
      <td>Java</td>
      <td>ImageJ plugin<br>
      To measure the concentration of genomic DNA fragments for next-generation sequencer using a photo of an agarose gel.
      This plugin is used in the <a href="https://pubmed.ncbi.nlm.nih.gov/33828169/"> article</a>.
      </td> 
    </tr>
  </table>
</details>
<details open>
  <summary><h2>Other scripts</h2></summary>
  <tr>
      <td>R scripts</td>
      <td><a href="https://github.com/YujiSue/RScript">Github</a></td>
      <td>R</td>
      <td>
      <ul>
      <li><a ref="">Statistical test</a></li>
      <li><a ref="">Make chart</a></li>
      <li><a ref="https://github.com/YujiSue/RScript/tree/master/ngs">For NGS analysis</a></li>
      </ul>
      </td> 
    </tr>

</details>
---
---

# リポジトリリスト 
---

## [slib](https://github.com/YujiSue/slib)

c++プログラミングサポート用のライブラリ  

* libsobj  
  > C++で疑似的な動的型付けでコードを書ける基本ライブラリ
  
* libsapp  
  > コマンドラインアプリを作成するためのライブラリ  

* libsnodeapp  
  > node.js上で動くnative addonsを作成するためのライブラリ  

* libsbioinfo  
  > バイオインフォマティクス関連の研究で使用しているライブラリ 

## [BioInfoTools](https://github.com/YujiSue/BioInfoTools)
バイオインフォマティクス関連の研究で使用しているプログラム

* [GenomeConverter](https://github.com/YujiSue/GenomeConverter)

  > FASTA形式のゲノム配列をバイナリファイルにエンコードするプログラム

* [GenomeExtract](https://github.com/YujiSue/BioInfoTools/tree/master/GenomeExtract)

  > [GenomeConverter](https://github.com/YujiSue/GenomeConverter)でエンコードされたファイルを用いて、ゲノムの一部または全塩基配列を抽出するプログラム


* [GFFParser](https://github.com/YujiSue/BioInfoTools/tree/master/GFFParser)

  > 入力されたgff3ファイルの情報を表示するプログラム

* [AnnotDBMaker ](https://github.com/YujiSue/BioInfoTools/tree/master/AnnotDBMaker)

  > 遺伝子アノテーションのためのsqlite3形式のデータベースを作成するプログラム

* [BioAnnotation](https://github.com/YujiSue/BioAnnotation)

  > [AnnotDBMaker ](https://github.com/YujiSue/BioInfoTools/tree/master/AnnotDBMaker)で生成されたデータベースを用いて対象領域のアノテーションを行うプログラム

* [GeneMapSVG](https://github.com/YujiSue/BioInfoTools/tree/master/GeneMapSVG)

  > [GenomeConverter](https://github.com/YujiSue/GenomeConverter)、[AnnotDBMaker ](https://github.com/YujiSue/BioInfoTools/tree/master/AnnotDBMaker)で生成されたバイナリゲノム配列とアノテーションデータベースを用いて、標的領域の遺伝子、転写構造、変異体の位置を表示するsvg(ベクター型画像)ファイルを作成するプログラム

* [VariantDetect](https://github.com/YujiSue/BioInfoTools/tree/master/VariantDetect)

  > 配列ファイル、特にサンガー配列の結果から変異型と位置を検出するプログラム

* [Sutoku](https://github.com/YujiSue/Sutoku)

  > 次世代シーケンサーで得られたBAMファイルから変異を検出するプログラム

## [Python](https://github.com/YujiSue/python)

* [DeletionFilter.ipynb](https://github.com/YujiSue/python/blob/master/DeletionFilter.ipynb)  
  
  > 次世代シーケンサーで検出した変異から機械学習で擬陽性を判定するためのコード

## [IJPlugIns](https://github.com/YujiSue/IJPlugIns)

ImageJのプラグインとして書いたJAVAのコード集

* [IJ_Subtract.java](https://github.com/YujiSue/IJPlugIns/blob/master/IJ_Subtract.java)  

  > スタック画像から、全画像の平均画像を引くサンプルプラグイン  
  
* [Open_Rois.java](https://github.com/YujiSue/IJPlugIns/blob/master/Open_Rois.java)  

  > ROIManagerに登録したROIを個別に新規画像として開くプラグイン

* [Stack_Editor.java](https://github.com/YujiSue/IJPlugIns/blob/master/Stack_Editor.java)  
  
  > ImageJのスタック画像から特定の画像を抽出するプラグイン  

* [Library_Measure.java](https://github.com/YujiSue/IJPlugIns/blob/master/Library_Measure.java)  

  > 次世代シーケンサーで用いるゲノムDNAの濃度をアガロース泳動写真から測定するためのライブラリ  
  (実際にThermoFisherScientificの 2% E-Gel Exの写真を使って利用中)

## [RScript](https://github.com/YujiSue/RScript)

研究で使用している統計ソフトR用のスクリプト集

## [Lecture](https://github.com/YujiSue/Lecture)

  Pythonプログラミングと、AIの講義用にGoogle Colaboratoryで作成したJupyter notebook集
