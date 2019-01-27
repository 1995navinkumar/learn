# General

## Why twisted pairs ?
* The wires are twisted pairs because the problem with wires that aren’t twisted is that they generate
magnetic fields that interfere with the signal carried on the wire. This
means that you can get electromagnetic interference and crosstalk—
both of which are bad for your network data.
When the wires are twisted, the magnetic field around the wire is
effectively disrupted so that any interference is reduced. The more
twists there are in the pairs, the better.

## What is the difference between bandwidth and speed ?
*  Bandwidth is a capacity; speed is
a rate. Bandwidth tells you the maximum
amount of data that your network can
transmit. Speed tells you the rate at which
the data can travel.

## Mbps and MBps ? 
* Megabits per second (Mbps)
is a bandwidth rate used in the
telecommunications and computer
networking field. One megabit equals one
million bursts of electrical current (aka
binary pulses). Megabytes per second
(MBps) is a data transfer rate used in
computing. One megabyte equals 1, 048,
576 bytes, and one byte equals 8 binary
digits (aka bits).

# Signal 
## Resistance
* Resistance is a measurement of how hard it is for electrons to
move through a wire. It’s measured in ohms, and represented by the
Greek letter omega, Ω. The higher the number of ohms, the harder
it is for electrons to move through the wire.
    * R = Pl/A (P = Resistivity of the material, l = length, A = area)

## Voltage
* Voltage is really electrical pressure.
*  voltage is the pressure that tries to make electrons flow.
It’s the push felt by the electrons. Think of voltage as the force that
moves the electrons in a circuit, and resistance as anything that might
slow them down, such as a broken wire.
* If we compare electron flow in a cable to water flow down a garden
hose, voltage is like the pressure of the water coming out the faucet,
and resistance is like the width of the garden hose.
* The signal on a network cable is just the change in voltage
over time.

## Noise
* Noise is unwanted signals on your network cables.
It comes from lots of different sources of electronic
energy. Most things that use electricity leak
electromagnetic energy. This is especially true of
electric things that move or have moving parts.

# Encoding
##  Why do we need to encode and decode signals?
* If we don’t encode and decode signals,
they come in as raw waveforms, i.e. 1’s &
0’s represented by voltages. We can’t do
much with such waveforms. We encode
and decode signals so that we have a way
to carry data on the signal. Networking is all
about sending messages, so encoding and
decoding are crucial to networking.

## Why don’t we just encode data in one way and stick to that?
*  Different encoding methods have
different advantages. Some encoding
methods are more efficient. Some methods
have better error correction. Over time,
better and better encoding methods come
about. These methods offer different
advantages and disadvantages over others.

##  How many different kinds of data encoding are there?
*  Data encoding comes in many flavors:
American Standard Code for Information
Interchange (ASCII), Binary Coded Decimal
(BCD), Differential Manchester Encoding
(DME), Extended Binary Coded Decimal
Interchange Code (EBCDIC), Feedback
Shift Register (FSR), Manchester Phase
Encoding (MPE), Non Return to Zero (NRZ),
Non Return to Zero Invertive (NRZ-I),
Return to Zero (RZ), and Unicode. Some
older encoding schemes in networking are
Manchester, NRZ, and NRZ-I.

##  So how do different encoding schemes help the various devices stay in sync?
*  By using an encoding scheme, a
device sending data on a network “embeds”
its clock into the signal. The clock is what
determines the 1’s & 0’s. Imagine if there
was just a string of 0’s using the NRZ
encoding scheme. This means that there is
just a low voltage. A device receiving this
signal would not know if this was really the
signal or if there was a break in the line.
* A signal with the clock embedded in the
signal allows the receiver to properly
decode the signal because the data is in
the transitions of voltages and not in just
the voltage level.

# MAC Address
* A media access control address (MAC address) of a device is a unique identifier assigned to a network interface controller (NIC) for communications at the data link layer of a network segments
* The company that manufactured
the NIC in your computer burned it into a
ROM chip on your NIC. Unless you’re an
electrical engineer with access to ROM
burning equipment, it will be pretty hard
to change the MAC address. You can,
however, fake out others on the network
by “spoofing” your MAC address. Typically
this requires a software utility. We don’t
recommend MAC address spoofing
because many companies regard it as a
security violation and it could result in legal
action.
* The Institute of Electrical and
Electronics Engineers Registration Authority
is in charge of issuing MAC addresses. 
*  There are 248 or
281,474,976,710,656 possible MAC
addresses. The IEEE does not expect to
exhaust the address space until 2100

##  Is there some type of data structure inside the packet?
* Protocol simply means a set way of
structuring information that is agreed upon
by the parties involved. So when a web
browser request a web page from a web
server, it uses the http protocol to request
that page, and the server responds with the
data using the http protocol. When a server
sends email, it uses the smtp protocol.
There are many different application type
protocols.

## Internet vs internet
* The Internet refers to
the big interconnected
space we use to send
data around the world.
The term “internet” refers
to at least two intranets
connected together by a
router.

## Physical Network vs Logical Network
* The physical
network is the
hardware such as
the cables, switches,
hubs, and routers.
* The logical
network is
the network
addressing stuff.

