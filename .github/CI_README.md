# VICAR GitHub Actions CI/CD Setup

Automated builds for VICAR using GitHub Actions.

## ✨ Zero Setup Required

GitHub Actions is automatically enabled - just push to trigger a build!

## 🚀 Quick Start

### Automatic Build
```bash
git push origin main
```

### Manual Build
1. Go to [Actions tab](../../actions)
2. Select "Build VICAR"
3. Click "Run workflow"
4. Choose options and run

## 📋 What Gets Built

- ✅ Core VICAR (RTL, TAE, subsystems)
- ✅ VISOR (109 Mars mission programs)
- ✅ Java components (JavaVicarIO, JadeDisplay, JADIS, SITH, JPIG)
- ✅ P1, P2, P3 image processing programs
- ✅ MARS subsystem

**Build Time:** ~1-2 hours

## 📦 Workflows

### `build-vicar.yml` (Main)
- Uses Red Hat UBI 8 container (RHEL 8 compatible)
- Downloads open source externals from GitHub releases
- Triggers: push, PR, weekly schedule, manual
- Stores logs and binaries as artifacts

**Build Environment:**
- Red Hat Universal Base Image 8 (UBI8)
- RHEL 8 / Oracle Linux 8 / CentOS 8 compatible
- Matches internal JPL build environment

## 📊 Monitor Builds

1. **Actions Tab** - See all workflow runs
2. **Click a run** - View detailed logs
3. **Download artifacts** - Get logs and binaries

## 📖 Documentation

Full documentation in [`.github/workflows/README.md`](.github/workflows/README.md):
- Customization options
- Adding camera models
- Caching strategies
- Troubleshooting guide
- Advanced features

## 💰 Cost

- **Public repos:** FREE unlimited builds ✅
- **Private repos:** 2,000 free minutes/month, then $0.008/min

## 🆘 Need Help?

- 📖 [Full Documentation](.github/workflows/README.md)
- 💬 [VICAR Google Group](https://groups.google.com/forum/#!forum/vicar-open-source/)
- 📧 vicar_help@jpl.nasa.gov
- 🐛 [File an Issue](../../issues)

## 📌 Status

[![Build VICAR](../../actions/workflows/build-vicar.yml/badge.svg)](../../actions/workflows/build-vicar.yml)

---

**Ready to build!** Push your code and watch it compile automatically. 🎉
