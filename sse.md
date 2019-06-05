
# Streaming SIMD Extensions

This is 

```
processor	: 0
vendor_id	: GenuineIntel
cpu family	: 6
model		: 158
model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
stepping	: 10
microcode	: 0x96
cpu MHz		: 945.615
cache size	: 9216 KB
physical id	: 0
siblings	: 12
core id		: 0
cpu cores	: 6
apicid		: 0
initial apicid	: 0
fpu		: yes
fpu_exception	: yes
cpuid level	: 22
wp		: yes
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
bogomips	: 4416.00
clflush size	: 64
cache_alignment	: 64
address sizes	: 39 bits physical, 48 bits virtual
power management:
```


```c++
!cat /proc/cpuinfo | less -20
```

    processor	: 0
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3422.395
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 0
    cpu cores	: 6
    apicid		: 0
    initial apicid	: 0
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 1
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3702.863
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 1
    cpu cores	: 6
    apicid		: 2
    initial apicid	: 2
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 2
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3556.265
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 2
    cpu cores	: 6
    apicid		: 4
    initial apicid	: 4
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 3
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3512.268
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 3
    cpu cores	: 6
    apicid		: 6
    initial apicid	: 6
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 4
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3642.787
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 4
    cpu cores	: 6
    apicid		: 8
    initial apicid	: 8
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 5
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3136.167
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 5
    cpu cores	: 6
    apicid		: 10
    initial apicid	: 10
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 6
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3535.684
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 0
    cpu cores	: 6
    apicid		: 1
    initial apicid	: 1
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 7
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 2251.174
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 1
    cpu cores	: 6
    apicid		: 3
    initial apicid	: 3
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 8
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 2202.563
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 2
    cpu cores	: 6
    apicid		: 5
    initial apicid	: 5
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 9
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 2413.537
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 3
    cpu cores	: 6
    apicid		: 7
    initial apicid	: 7
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 10
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 1974.963
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 4
    cpu cores	: 6
    apicid		: 9
    initial apicid	: 9
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    
    processor	: 11
    vendor_id	: GenuineIntel
    cpu family	: 6
    model		: 158
    model name	: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
    stepping	: 10
    microcode	: 0x96
    cpu MHz		: 3336.891
    cache size	: 9216 KB
    physical id	: 0
    siblings	: 12
    core id		: 5
    cpu cores	: 6
    apicid		: 11
    initial apicid	: 11
    fpu		: yes
    fpu_exception	: yes
    cpuid level	: 22
    wp		: yes
    flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb invpcid_single pti ssbd ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp flush_l1d
    bugs		: cpu_meltdown spectre_v1 spectre_v2 spec_store_bypass l1tf
    bogomips	: 4416.00
    clflush size	: 64
    cache_alignment	: 64
    address sizes	: 39 bits physical, 48 bits virtual
    power management:
    

