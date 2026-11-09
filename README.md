### 野坂 健成 (Kensei Nosaka)

筑波大学 修士1年。予測精度だけでなく「その予測でどんな意思決定ができるか」で評価する、**数理最適化 × 機械学習**に取り組んでいます。

- **関心領域**: Decision-Focused Learning、組合せ最適化、小規模データでの検証設計
- **Kaggle**: Competitions Expert・銅メダル 2 個 — Santa 2025（配置最適化, 287/3357位）、CSIRO Image2Biomass（画像回帰, 253/3805位）

#### 主なリポジトリ

| リポジトリ | 課題 | アプローチ |
|---|---|---|
| [dfl-portfolio](https://github.com/nuummm/dfl-portfolio) | リターン予測を、予測誤差ではなくポートフォリオの意思決定コストで学習する | 平均分散 QP を KKT 条件で埋め込んだ一段化モデル（Pyomo）。閉形式解と総当たりの参照解で検証 |
| [csiro-image2biomass](https://github.com/nuummm/csiro-image2biomass) | 牧草画像 357 枚から 5 種類のバイオマス量を推定する | DINOv3 の凍結埋め込み、日付グループ CV、ターゲット間の加法制約の扱い |
| [santa2025-tree-packing](https://github.com/nuummm/santa2025-tree-packing) | 1〜200 個の非凸多角形を最小の正方形に詰める | Numba による SAT 衝突判定と焼きなまし法、公式互換の検証器 |
| [group-scheduler](https://github.com/nuummm/group-scheduler) | 1 つの部屋を共有する定例ミーティング群の時間割を決める | 自作の分枝限定法（Cloudflare Workers 上で動作）、厳密解オラクルとの比較で検証 |

**使用技術**: Python（NumPy, scikit-learn, PyTorch, Numba, Pyomo）・TypeScript（React, Cloudflare Workers）・uv・pytest・GitHub Actions
