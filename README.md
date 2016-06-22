# asakusa-template

Asakusa Frameworkのテンプレートプロジェクト。


## Base Asakusa FW template 

- asakusa-mapreduce-template-0.8.0.tar.gz


## 環境構築手順

### 1. ASAKUSA_HOMEを定義する

```
export ASAKUSA_HOME=/usr/local/asakusa
```

MacでEclipseに環境変数を適用するためには、以下のコマンドを実行する。

```
mkdir /usr/local/asakusa
launchctl setenv ASAKUSA_HOME /usr/local/asakusa
```

### 2. コンソールで以下のコマンドを実行

```
cd <project directory>
./gradle installAsakusafw
gradle eclipse
```

### 3. Eclipseでプロジェクトをインポート

Eclipseのプロジェクトをimportする場合は、Gradleのimport projectを利用する。

