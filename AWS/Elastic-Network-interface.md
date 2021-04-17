# Elastic Network Interface

まずは、ENIの前にNIC(Network Interface Card)の話から、
NICとは物理的な環境におけるネットワークインターフェースのことで、
サーバーに複数枚挿すことで役割に応じてIPアドレスを複数もたせる事もできる。
ENIも同様のことを仮想環境で構築することができますが、実態は、AWSが管理してい
物理的なサーバーになります。


各インスタンスには、プライマリネットワークインターフェイスと呼ばれるデフォル
ネットワークインターフェイスがある。これにパブリックIPv4アドレスを割り当てる


ネットワークインターフェイスはサブネットで作成でき、
作成後のネットワークインターフェイスを別のサブネットに移動することはできません
ネットワークインターフェイスは、同じAZのインスタンスのみにアタッチできる。


