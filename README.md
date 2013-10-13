# cmd-dict

command line dictionary for Chinese &lt;=> English

## install

pre-requirements

- python3; it's a better python than python2

- pip3 install -r requirements.txt; 'pip3' is your python3 pip

- youdao translation API, get key here: http://fanyi.youdao.com/openapi?path=data-mode

install

    git clone https://github.com/typd/cmd-dict.git
    cp cmd-dict/dict /usr/local/bin/dict
    echo [key-from] >> ~/.dict_config
    echo [key] >> ~/.dict_config


## usage

    >> dict 'hello world'
    ----------------
      你好世界
    e.g.
      hello world       : 你好世界; 举个例子; 开始
      Hello   World     : 会写的人多了去了
      Hello Kitty World : 凯蒂猫气球世界
    --------------------------------

    >> dict 数据接口
    ----------------
      [计] data interface
      Data interface
      |shù jù jiē kǒu|
    e.g.
      数据接口　　　　 : data interface; DATAPORTI; USB
      光纤分布数据接口 : FDDI; fiber distributed data interface; FDD
      光波数据接口　　 : LDI LightwaveDataInterface
    --------------------------------

or you can use shell mode

    >> dict
    --------------------------------
    Look up: hello world
    ----------------
      你好世界
    e.g.
      hello world       : 你好世界; 举个例子; 开始
      Hello   World     : 会写的人多了去了
      Hello Kitty World : 凯蒂猫气球世界
    --------------------------------

    --------------------------------
    Look up: 数据接口
    ----------------
      [计] data interface
      Data interface
      |shù jù jiē kǒu|
    e.g.
      数据接口　　　　 : data interface; DATAPORTI; USB
      光纤分布数据接口 : FDDI; fiber distributed data interface; FDD
      光波数据接口　　 : LDI LightwaveDataInterface
    --------------------------------

## note

only support Chinese <=> English translation
