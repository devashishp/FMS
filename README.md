# FMS
Resources for my talk on Controllers, ZNS, and FDP SSDs at FMS 2023

## Motivation:
- [The bleak future of NAND Flash Memory](https://www.usenix.org/conference/fast12/bleak-future-nand-flash-memory)
- [Tiny-Tail Flash: Near-Perfect Elimination of Garbage Collection Tail Latencies in NAND SSDs](https://dl.acm.org/doi/pdf/10.1145/3121133)
- [PANEL: Flexible Data Placement using NVM Express® - Implementation Perspective](https://www.youtube.com/watch?v=R0GHuKwi3Fc)
- [From Open-Channel SSDs to Zoned Namespaces](https://www.usenix.org/conference/vault19/presentation/bjorling)

## Zoned Storage:
- [zonedstorage.io](https://zonedstorage.io)
- [Don’t Be a Blockhead: Zoned Namespaces Make Work on Conventional SSDs Obsolete](https://sigops.org/s/conferences/hotos/2021/papers/hotos21-s07-stavrinos.pdf)
- [Append is Near: Log-based Data Management on ZNS SSDs](https://www.cidrdb.org/cidr2022/papers/p93-purandare.pdf)
- [ZNS: Avoiding the Block Interface Tax for Flash-based SSDs](https://www.usenix.org/conference/atc21/presentation/bjorling)
- [ZNSwap: Unblock your swap](https://www.usenix.org/conference/atc22/presentation/bergman)

### Emulation
- [QEMU](https://zonedstorage.io/docs/tools/qemu)
- [null_blk](https://zonedstorage.io/docs/getting-started/zbd-emulation)
- [ConfZNS](https://dl.acm.org/doi/10.1145/3579370.3594772)

### Libraries
- [libzbd](https://github.com/westerndigitalcorporation/libzbd)
- [libnvme](https://github.com/linux-nvme/libnvme)
- [xNVMe](https://xnvme.io/)

### Filesystems
- [btrfs](https://zonedstorage.io/docs/linux/fs)
- [f2fs](https://zonedstorage.io/docs/linux/fs)
- [zenfs](https://github.com/westerndigitalcorporation/zenfs)
- [zonefs](https://www.kernel.org/doc/html/next/filesystems/zonefs.html)

## Flexible Data Placement (FDP)
- [NVMe Streams](https://www.usenix.org/system/files/conference/fast18/fast18-rho.pdf)
- [NVMe TP 4146 Flexible Data Placement](https://nvmexpress.org/wp-content/uploads/NVM-Express-2.0-Ratified-TPs-07252023.zip)
- [Flexible Data Placement OCP 2023 Storage talks](https://www.opencompute.org/events/past-events/2023-ocp-storage-tech-talks)

### Possible hint interfaces
- [RW_Lifetime_Hint](https://lwn.net/Articles/726477/)
- [fadvise(2)](https://linux.die.net/man/2/fadvise)

### Emulation
- [Qemu 8](https://www.qemu.org/)

## Hint Generation
- [Compaction-aware zone allocation for LSM based key-value store on ZNS SSDs](https://dl.acm.org/doi/abs/10.1145/3538643.3539743)
- [Efficient Key-Value Data Placement for ZNS SSD ](https://www.mdpi.com/2076-3417/11/24/11842)
