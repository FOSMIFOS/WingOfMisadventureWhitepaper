# MISADGEN1 プレミント

ゲームデータベースは、**2022/05/13**に、各NFTの以下の属性を入力しました。

{% file src="../.gitbook/assets/immutable (1) (1).pdf" %}

生成コード:

```
            List<NFT> nft_list = new List<NFT>();

            Random rd = new Random();

            for (int i = 0; i < 2500; i++)
            {
                NFT nft_data;

                nft_data.gen = 1;
                nft_data.type = (byte)rd.Next(0, 3);
                nft_data.rarity = 0;
                nft_data.skill = (byte)rd.Next(0, 100);
                nft_data.affinity = (byte)rd.Next(0, 100);
                nft_data.willpower = (byte)rd.Next(0, 100);
                nft_data.heredity = (byte)rd.Next(0, 100);
                nft_data.personality = (byte)rd.Next(0, 100);
                nft_data.hearth = (byte)rd.Next(0, 100);

                nft_list.Add(nft_data);
            }

            for (int i = 0; i < 1350; i++)
            {
                NFT nft_data;

                nft_data.gen = 1;
                nft_data.type = (byte)rd.Next(0, 3);
                nft_data.rarity = 1;
                nft_data.skill = (byte)rd.Next(0, 100);
                nft_data.affinity = (byte)rd.Next(0, 100);
                nft_data.willpower = (byte)rd.Next(0, 100);
                nft_data.heredity = (byte)rd.Next(0, 100);
                nft_data.personality = (byte)rd.Next(0, 100);
                nft_data.hearth = (byte)rd.Next(0, 100);

                nft_list.Add(nft_data);
            }

            for (int i = 0; i < 1100; i++)
            {
                NFT nft_data;

                nft_data.gen = 1;
                nft_data.type = (byte)rd.Next(0, 3);
                nft_data.rarity = 2;
                nft_data.skill = (byte)rd.Next(0, 100);
                nft_data.affinity = (byte)rd.Next(0, 100);
                nft_data.willpower = (byte)rd.Next(0, 100);
                nft_data.heredity = (byte)rd.Next(0, 100);
                nft_data.personality = (byte)rd.Next(0, 100);
                nft_data.hearth = (byte)rd.Next(0, 100);

                nft_list.Add(nft_data);
            }

            for (int i = 0; i < 50; i++)
            {
                NFT nft_data;

                nft_data.gen = 1;
                nft_data.type = (byte)rd.Next(0, 3);
                nft_data.rarity = 3;
                nft_data.skill = (byte)rd.Next(0, 100);
                nft_data.affinity = (byte)rd.Next(0, 100);
                nft_data.willpower = (byte)rd.Next(0, 100);
                nft_data.heredity = (byte)rd.Next(0, 100);
                nft_data.personality = (byte)rd.Next(0, 100);
                nft_data.hearth = (byte)rd.Next(0, 100);

                nft_list.Add(nft_data);
            }
            
            nft_list.Shuffle();
```
