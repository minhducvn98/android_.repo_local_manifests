Mokee Open Source Manifest - Project Vee3
========================
Local manifests to build Android KitKat 4.4 to L3 II Single/Dual

To initialize Mokee OS Repo:

    repo init -u https://github.com/MoKee/android.git -b kk_mkt

To initialize Vee3 Repo's:

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/TeamVee/android_.repo_local_manifests/kk_mkt/local_manifest.xml

To sync:

    repo sync
