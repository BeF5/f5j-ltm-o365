================================================
1. O365向けOutbound通信対策
================================================

O365宛通信は大量にコネクションをはるためProxyサーバへの負荷が懸念されます。回避策としてO365はBIG-IP経由で直接アクセス、その他のWebサイトへの通信は既存のProxyサーバ経由とすることでセッション数枯渇などのネットワーク機器への影響を回避します。本書で設定サンプルをご案内します。


.. toctree::
   :titlesonly:
   :caption: 目次:
   :glob:

   module**/module**
