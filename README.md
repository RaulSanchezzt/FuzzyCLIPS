# FuzzyClips

> FuzzyCLIPS is a fuzzy logic extension of the CLIPS (C Language Integrated Production System) expert system shell from NASA. It was developed by the Integrated Reasoning Group of the Institute for Information Technology of the National Research Council of Canada and has been widely distributed for a number of years. It enhances CLIPS by providing a fuzzy reasoning capability that is fully integrated with CLIPS facts and inference engine allowing one to represent and manipulate fuzzy facts and rules. FuzzyCLIPS can deal with exact, fuzzy (or inexact), and combined reasoning, allowing fuzzy and normal terms to be freely mixed in the rules and facts of an expert system. The system uses two basic inexact concepts, fuzziness and uncertainty. It has provided a useful environment for developing fuzzy applications but it does require significant effort to update and maintain as new versions of CLIPS are released.

## How to install FuzzyClips on Linux

First install the required packages:

```bash
sudo apt install git libncurses5-dev
```

Then, clone this repo and change the directory to `source`:

```bash
git clone git@github.com:RaulSanchezzt/FuzzyCLIPS.git && cd FuzzyCLIPS/source
```

**Compile** from source and make it **executable**.

```bash
make fzclips && sudo chmod +x fz_clips
```

Now you can execute this program:

```bash
~/FuzzyCLIPS/source/fz_clips
        FuzzyCLIPS V6.10d (10/22/2004)
FuzzyCLIPS>
```

I would recommend to create an **alias** on your `.bashrc`:

```bash
echo -e "\n alias fuzzyclips='~/FuzzyCLIPS/source/fz_clips'" >> ~/.bashrc
```

---

> - forked from [rorchard/FuzzyCLIPS](https://github.com/rorchard/FuzzyCLIPS)
